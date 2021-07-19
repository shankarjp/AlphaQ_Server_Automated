FROM ubuntu
RUN apt-get update
RUN apt-get install -y acl
RUN apt-get install -y wget

COPY genUser.sh genUser.sh
COPY permit.sh permit.sh
COPY schedule.sh schedule.sh
COPY attendance.sh attendance.sh
COPY genMoM.sh genMoM.sh
COPY genMoM1.sh genMoM1.sh
COPY aliases_and_crontabs.sh aliases_and_crontabs.sh

RUN ./genUser.sh
RUN ./permit.sh
RUN ./schedule.sh
RUN ./attendance.sh
RUN ./genMoM.sh
RUN ./genMoM1.sh
RUN ./aliases_and_crontabs.sh

