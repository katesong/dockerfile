FROM 10.8.90.189:5000/st.win/weblogic-lott:master
USER weblogic

ADD war /home/weblogic/war

ARG SERVICE_NAME=
ARG WAR_NAME=

RUN /home/weblogic/deploy/deploy.sh

ENTRYPOINT sh /home/weblogic/restart-weblogic.sh && /bin/bash