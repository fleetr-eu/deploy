## Fleetr setup on Scaleway

### Requirements

The following requirements must be met before you can execute this playbook:

* Ansible 2.3 or higher on control machine
* Scaleway CLI on the control machine

### Usage

#### Scaleway

You need to acquire your Scaleway authorization token and organization id.
You can get both from the .scwrc file that will be created when using the
Scaleway CLI (https://github.com/scaleway/scaleway-cli#quick-start).

```
export SCALEWAY_ORG_ID=1234
export SCALEWAY_AUTH_TOKEN=1234
ansible-playbook full.yml --extra-vars=@vars.yml
```
