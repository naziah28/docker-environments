FROM py38

RUN apt-get update
RUN apt install -y libgl1-mesa-glx

COPY requirements.txt ./
RUN pip3 install -r requirements.txt
