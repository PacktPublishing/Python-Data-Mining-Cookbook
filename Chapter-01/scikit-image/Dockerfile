FROM ubuntu:16.04

RUN apt-get update && \
apt-get install -y pkg-config libopenblas-dev liblapack-dev git-core build-essential gfortran python-dev curl libfreetype6-dev libjpeg-dev libhdf5-dev liblzo2-dev libbz2-dev && \
curl https://bootstrap.pypa.io/get-pip.py | python && \
pip install cython && \
pip install numpy && \
pip install six && \
pip install pillow && \
pip install scikit-image && \
pip install scipy && \
pip install scikit-learn && \
pip install matplotlib && \
pip install ipython[all] && \
pip install h5py && \
pip install pandas && \
pip install numexpr && \
pip install tables
