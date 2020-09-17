FROM jenkins/jenkins:lts
RUN apt-get update && apt-get install -y vim
RUN chown -R 1000:1000 /home/jenkins_workspace
RUN chown -R 1000:1000 /var/run/docker.sock