### Hands On Ansible
First task that needs to be ran after firing up a DigitalOcean Droplet

After the Droplet is fired, when trying to test the IP with `ping` you'll get the following error:
```json
➜  open-source/test  ansible all -m ping -i inventory
46.101.209.8 | FAILED! => {
    "changed": false,
    "failed": true,
    "module_stderr": "",
    "module_stdout": "/bin/sh: 1: /usr/bin/python: not found\r\n",
    "msg": "MODULE FAILURE",
    "parsed": false
}
```

This repo has been created to solve this issue


###### Resources
- [Ansible fails with /bin/sh: 1: /usr/bin/python: not found | StackOverflow][1]

[1]: http://stackoverflow.com/a/34402816/2733115
