FROM pytorch/pytorch:1.9.0-cuda10.2-cudnn7-runtime
RUN apt-get update
RUN apt-get install ffmpeg libsm6 libxext6  -y
RUN pip install rudalle==0.4.0 > /dev/null

