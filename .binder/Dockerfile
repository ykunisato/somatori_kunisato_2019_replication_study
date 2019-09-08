FROM rocker/binder:3.6.0
LABEL maintainer='Yoshihiko Kunisato'
USER root
RUN apt-get update \
&& apt-get install -y fonts-ipaexfont
COPY . ${HOME}
RUN chown -R ${NB_USER} ${HOME}
USER ${NB_USER}
RUN wget https://github.com/ykunisato/somatori_kunisato_2019_replication_study/raw/master/DESCRIPTION && R -e "options(repos = list(CRAN = 'http://mran.revolutionanalytics.com/snapshot/2019-08-17/')); devtools::install_deps()"
