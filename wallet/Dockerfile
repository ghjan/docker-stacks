# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.

FROM ubuntu/xenial

MAINTAINER Jupyter Project <jupyter@googlegroups.com>

USER root

# Install all OS dependencies for fully functional notebook server
RUN apt-get update && apt-get install -yq --no-install-recommends \
    build-essential \
    git \
    python-dev \
    vim \
    unzip \
    qtbase5-dev \  
    qt5-default \
    qtdeclarative5-dev \
    qml-module-qtquick-controls \
    qml-module-qtquick-xmllistmodel \
    qttools5-dev-tools \
    qml-module-qtquick-dialogs \
    qml-module-qt-labs-settings \
    libqt5qml-graphicaleffects \
    && apt-get clean && \
    rm -rf /var/lib/apt/lists/*


