# set up Jenkins

set up Jenkins

## Provides

* jenkins
* openjdk8

## Requires

1. Ansible(checked 2.2)
2. CentOS 6.5 later

## Usage

### Get the code
`$ git clone https://github.com/sugitk/ansible-jenkins.git`

### change hosts file

```
[jenkins]
192.168.1.20
```

### Run the Playbook

`$ ansible-playbook -i hosts site.yml`

