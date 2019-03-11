FROM softcrylicqa/headless-chrome

MAINTAINER Softcrylic

#USER seluser

USER root

COPY start-selenium-standalone.sh /opt/bin/start-selenium-standalone.sh

COPY selenium.conf /etc/supervisor/conf.d/

EXPOSE 4444
