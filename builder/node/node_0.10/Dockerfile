FROM bradrydzewski/base

WORKDIR /home/ubuntu
USER ubuntu
ADD nodejs.sh /etc/drone.d/

# we currently install node 0.10 in the base image
# so we'll comment this out for now
#RUN /bin/bash -c ". /home/ubuntu/nvm/nvm.sh && nvm install 0.10"
