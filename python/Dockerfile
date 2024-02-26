# Base
FROM python:3.10

# Update
RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6 libgl1 -y
RUN apt-get install apt-utils software-properties-common -y
RUN apt-get install iputils-ping nmap netcat-openbsd -y
RUN apt-get install vim wget curl git -y

# Common dependencies
RUN pip install requests==2.31.0
RUN pip install fastapi==0.110.0
RUN pip install uvicorn==0.27.1
RUN pip install aiofiles==23.2.1
RUN pip install injectable==3.4.7
RUN pip install SQLAlchemy==2.0.27
RUN pip install yoyo-migrations==8.2.0
RUN pip install psycopg2-binary==2.9.9
RUN pip install python-multipart==0.0.9
RUN pip install numpy==1.26.4
RUN pip install opencv-python==4.9.0.80
RUN pip install xlrd==1.2.0
RUN pip install pyzipcode==3.0.1
RUN pip install google-cloud-bigquery==3.11.3
RUN pip install openpyxl==3.0.10
RUN pip install pika==1.3.2
RUN pip install formulas==1.2.7
RUN pip install bcrypt==4.1.2
RUN pip install python-jose[cryptography]==3.3.0

# Our libraries
RUN pip install simplestr==0.5.0
RUN pip install omoide-cache==0.1.3
RUN pip install tekleo-common-message-protocol==0.0.0.6
RUN pip install tekleo-common-utils==0.0.2.4
RUN pip install tekleo-services-client==0.0.0.1
