# DataLogger
A C++ implementation of a data-logger which reads values from sensors and other data-sources to store them in a InfluxDB database

# CPP2InfluxDB
C++ Implementation of database interface for an influx-database

[![Build Status](https://travis-ci.org/open-pete/DataLogger.svg?branch=development)](https://travis-ci.org/open-pete/DataLogger) [![Coverage Status](https://coveralls.io/repos/github/open-pete/DataLogger/badge.svg?branch=development)](https://coveralls.io/github/open-pete/DataLogger?branch=development)

## Requirements 

 1. Installation of qt
 2. Installation of python3-pip and gitpython

## Setup / Clone & Compile 

```bash
# set variables
repoName="DataLogger"
repoURL="https://github.com/open-pete/DataLogger.git"
branch="master"
manifest="default.xml"

# clone this repository
git clone ${repoURL}
cd ${repoName}

# download all depency repos
git clone https://github.com/mezorian/EasyDepend.git
cp EasyDepend/*.py .
python3 example.py

# build
source /opt/qt55/bin/qt55-env.sh
/opt/qt55/bin/qmake
make clean
make

# run
./DataLogger

```

