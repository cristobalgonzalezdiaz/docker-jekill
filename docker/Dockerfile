FROM jekyll/jekyll:latest
LABEL Description="jekyll Project"
LABEL Maintainer="cristobal@cristobal-lab.com.au"

#ENV HOME /root

#SHELL [ "/bin/bash", "-c"]

RUN gem install webrick

# this is for timezone config
#ENV DEBIAN_FRONTEND=noninteractive 
#ENV TZ=Australia/Melbourne


# update 
#RUN apt-get update
# install curl 
#RUN apt-get -y install curl
# get install script and pass it to execute: 
#RUN curl -sL https://deb.nodesource.com/setup_20.x | bash
# and install node 
#RUN apt-get -y install nodejs
# confirm that it was successful 
#RUN node -v
# npm installs automatically 
#RUN npm -v
