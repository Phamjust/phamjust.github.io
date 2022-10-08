# Hello there! 👋

This repository stores code for my static site that hosts my resume.

## About this website
This site is generated with [Hugo](https://gohugo.io/) and hosted through an Nginx websever, using a Digital Ocean Droplet.

### Purpose
* Learn the basics of devops through a hands on project.

### Steps Taken
* Provision droplet with Terraform.
* Setup DNS for Domain with Terraform.
* Using Ansible, configure Droplet user account, SSH key, and setup Nginx webserver.
* Setup GitHub Actions to push the generated site to the droplet on every commit.
* Enable HTTPS(SSL) with 'Let's Encrypt'
