# WFHT Ollama Delployment Repo for (Ubuntu 22.04)

Working with new AI technology requires the ability to experiment and prototype, which requires repeatable deployments. This repo helps with the setup of llama, models and Open-webUI through the use of Ansible scripts. 

## Video Tutorial

[![Llama 3 Automated Deployment](https://img.youtube.com/vi/9pmi-b9U0FI/maxresdefault.jpg)](https://www.youtube.com/embed/9pmi-b9U0FI)
link: - https://www.youtube.com/watch?v=9pmi-b9U0FI

## Files

-  apt-update.yaml - Updates APT packages on an Ubuntu machine.
-  cuda-install.yaml - Installs the CUDA Kit version 12.4.
-  docker-install.yaml - Installs Docker directly from Docker.
-  inventory.ini - An example inventory file that can be modified as needed.
-  LICENSE - License file.
-  llamacpp-install.yaml - Install playbook that downloads and compiles llamacpp [Warning: Work In Progress!]
-  llamacpp-model-install.yaml - Playbook to install models desired for llamacpp.
-  nginx-proxy-install.yaml - Installs the nginx proxy manager if desired
-  ollama-install.yaml - Ollama install playbook that will provide a complete llama3 install with the latest llam3 8b model and Open-WebUI. Everything should be ready for use after it runs.
-  README.md

## Future updates

TODOS:
- [ ] Creation of cloud VMs on Azure and Digital ocean via a playbook
- [ ] Update the video tutorial link once the YT video is complete  


## Reference Links:

### Hardware Reviews

Link - https://tech.workfromhometech.io

### Work From Home Tech YouTube Channel

Ubuntu Install for MAAS Setup: https://www.youtube.com/watch?v=ASgwQMN34JM

### Work From Home Tech YouTube Channel Introduction

[![WFHT Channel Intro](https://img.youtube.com/vi/7zls5w3Ar1U/maxresdefault.jpg)](https://www.youtube.com/embed/7zls5w3Ar1U) 

Link - https://youtu.be/7zls5w3Ar1U

### Main Work From Home Tech Website

https://workfromhometech.io

![GitHub last commit](https://img.shields.io/github/last-commit/Work-From-Home-Tech/ollama-deploy)



