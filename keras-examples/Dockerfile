FROM 763104351884.dkr.ecr.us-west-2.amazonaws.com/tensorflow-training:1.14.0-gpu-py36-cu100-ubuntu16.04

COPY cifar10_resnet.py /opt/training/cifar10_resnet.py

WORKDIR /opt/training

ENTRYPOINT ["python", "cifar10_resnet.py"]