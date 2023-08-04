Bootstrap:docker
From:hailgenetics/hail:0.2.120

%labels
MAINTAINER Thomas Green

%environment

%runscript
exec /bin/bash /bin/echo "Not supported"

%post
mkdir /scratch
mkdir /software
mkdir /apps
mkdir /app

hail-pip-install jupyterlab

