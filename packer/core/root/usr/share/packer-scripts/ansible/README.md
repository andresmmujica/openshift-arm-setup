# Ansible Packer image

This repository contains Temaples for Ansible images for general usage and OpenShift.

## Environment variables

The image recognizes the following environment variables that you can set during
initialization by passing `-var 'VAR=VALUE'` to the Packer build command.

| Variable name | Description |
| :------------ | ----------- |
|               |             |

## Usage

```sh
packer build -only=azure-arm -var rhsm_username=me@something.com -var rhsm_password=mypassword template-ami.json
```
