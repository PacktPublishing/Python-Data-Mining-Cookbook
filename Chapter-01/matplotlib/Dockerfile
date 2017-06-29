FROM ubuntu:16.04

# Update the repository sources list
RUN apt-get update

# Install pip, Python and matplotlib required libraries
RUN apt-get update && apt-get install -y python python-dev python-pip \
    libxft-dev libfreetype6 libfreetype6-dev

# Install matplotlib
RUN pip install 'matplotlib'
