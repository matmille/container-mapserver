## Implementing a MapServer (mapserver.org) inside of a container

This repository is meant to showcase performing a package build inside the OpenShift Container Platform

## What is in this repository?

This repo contains a Dockerfile for perform a container build and a Ansible playbook to do the heavy lifting
Map data pulled from NASA (bluemarble) and the Census (shapefiles)

## Prerequisite

This project requires the httpd-24-rhel7 container image provided by Red Hat Software Collections via the Red Hat container registry
https://access.redhat.com/containers/?tab=overview#/registry.access.redhat.com/rhscl/httpd-24-rhel7

## Getting started (example)

```
oc login <your login parameters to your OpenShift cluster>
oc new-project <project name>
oc new-build https://github.com/matmille/container-mapserver.git
```
