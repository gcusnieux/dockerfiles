# Ubuntu with default volumes ready to add-apt-repository and wget

FROM ubuntu:14.04

MAINTAINER Guillaume Cusnieux <@gcusnieux>

# Default volumes
RUN mkdir -p /dk-scripts /dk-datas /dk-logs

# Needed for add-apt-repository and wget
RUN apt-get update -y
RUN apt-get install -y software-properties-common wget