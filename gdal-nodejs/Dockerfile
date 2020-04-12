FROM osgeo/gdal:ubuntu-full-latest

LABEL author="Jorge Jiménez <otrojotaj@gmail.com>"

RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt -y install nodejs
RUN apt -y install git

RUN update-alternatives --install /usr/bin/python python /usr/bin/python3 10
RUN apt-get install -y python3-pip
#RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
#RUN ["python", "get-pip.py"]
RUN ["pip3", "install", "numpy"]
RUN ["pip3", "install", "motuclient"]