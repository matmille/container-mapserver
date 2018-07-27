## Implementing a MapServer (mapserver.org) Open Source map platform inside of a container

This repository is meant to showcase performing a package build inside the OpenShift Container Platform

## What is in this repository?

This repo contains a Dockerfile for perform a container build and a Ansible playbook to do the heavy lifting

## Getting started (example)

```
oc login <your login parameters to your OpenShift cluster>
oc new-project <project name>
oc new-build https://github.com/matmille/container-mapserver.git
```
