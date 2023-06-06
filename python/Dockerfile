# Base
FROM python:3.10

# Update
RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6 libgl1 -y
RUN apt-get install apt-utils software-properties-common -y
RUN apt-get install iputils-ping nmap netcat -y
RUN apt-get install vim wget curl git -y

# Common dependencies
RUN pip install requests==2.25.1
RUN pip install fastapi==0.95.1
RUN pip install uvicorn==0.22.0
RUN pip install aiofiles==23.1.0
RUN pip install injectable==3.4.7
RUN pip install SQLAlchemy==2.0.12
RUN pip install yoyo-migrations==8.2.0
RUN pip install psycopg2-binary==2.8.6
RUN pip install python-multipart==0.0.5
RUN pip install numpy==1.21.5
RUN pip install opencv-python==4.7.0.72
RUN pip install xlrd==1.2.0
RUN pip install pyzipcode==3.0.1

# Our libraries
RUN pip install simplestr==0.5.0
RUN pip install omoide-cache==0.1.3
RUN pip install tekleo-common-message-protocol==0.0.0.6
RUN pip install tekleo-common-utils==0.0.2.4
RUN pip install tekleo-services-client==0.0.0.1
