# v2ray ansible
This repository provides the ansible playbook to provision v2ray servers.

## Reuirements
You'll need `ansible 2.10.8` with `ansible-galaxy` installed. In order to prepare the playbook you must install the requirements using the following command:
```shell
ansible-galaxy install -r requirements.yaml
``` 

## Usage

First set the your server ip in the `inventory/inventory.yaml` and then create your `config.json` inside `inventory/files/v2ray`. You can also use one of sample configs in [v2ray-config-examples](https://github.com/xesina/v2ray-config-examples).

```shell
ansible-playbook site.yaml
```
