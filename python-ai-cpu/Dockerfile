# Base
FROM jpleorx/base-python

# Common AI dependencies
RUN pip install --no-cache-dir torch==2.0.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
RUN pip install --no-cache-dir torchvision==0.15.1+cpu -f https://download.pytorch.org/whl/torch_stable.html
RUN pip install google-cloud-storage==2.8.0

# Detectron
RUN mkdir /detectron2_temp
WORKDIR /detectron2_temp
RUN git clone https://github.com/facebookresearch/detectron2.git
RUN python -m pip install -e detectron2

# Our libraries
RUN pip install simplestr==0.5.0
RUN pip install omoide-cache==0.1.3
RUN pip install tekleo-common-message-protocol==0.0.0.6
RUN pip install tekleo-common-utils==0.0.2.4
RUN pip install tekleo-services-client==0.0.0.1
RUN pip install tekleo-common-utils-ai==0.0.0.7