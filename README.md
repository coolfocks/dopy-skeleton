# Skeleton pro python3 na dockeru

Holátko pro dev na py3 s dockerem

Naklonovat a jedem

Info o [pyDockeru](https://hub.docker.com/_/python)

# Setup

Nejdřív buildnem repo pro docker

    docker build -t my-python-app .


Pak ho spustíme

    docker run -it --rm --name my-running-app my-python-app

Úpravy v requirements.txt požadují rebuild

Místo *my-python-app* si jméno můžeš zvolit jj
