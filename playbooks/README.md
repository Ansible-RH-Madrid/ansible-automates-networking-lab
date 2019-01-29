# For Instructors

## How to customize the labs

- Clone the repo and get into it
- Create every student files as students attend to the Hands-on (sample) inside of students folder
- 02.yml (the name is irrelevant)
```
tower_instance: '58.96.149.147'
tower_user: 'adm1n'
tower_password: 'ans1ble'
ansible_user: 'stud3nt1'
```

- Execute this commands:
```
cd playbooks
ansible-playbook tower_env.yml
```

- Magic happens :)
