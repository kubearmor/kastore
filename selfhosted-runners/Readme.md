# Quick Install Guide for the runners we in kubearmor repository

This works for any platform i.e., Linux, Windows, MacOS that is supported by Vagrant

## Pre-requisite

[Download and Install Vagrant](https://www.vagrantup.com/downloads).

## 1. Download Vagrantfile

Download the vagrant file under apparmor and bpflsm folders and keep them in different folders


## 2. Start vagrant

Execute `vagrant up` in the same folder where `Vagrantfile` is located. 
>**Note** You might need to update the configurations of the Vagrant file suited to your machine

```
$ vagrant up

```
</details>

## 3. Add new runners to your repository using this guide

Follow [Adding self-hosted runners](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/adding-self-hosted-runners).