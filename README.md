## Deploying a Simple HTML File using Ansible and Apache

### Write the inventory file 
`inventory`
- wrote the playbook but due to complications ended up using localhost alone instead of the IP
### Write the Playbook
`Playbook.yaml`
- Wrote the playbook defining the name, host, tasks for:
    - installing Apache either on Ubuntu, CentOS or MacOS as httpd
    - starting the Apache/httpd server
    - deploying the html file 


### Write the simple HTML file
`index.html`

## Command 

````
$ ansible-playbook -i localhost, -c local Playbook.yaml

or 

ansible-playbook -i localhost, -c local Playbook.yaml --ask-become-pass

````

## Acknowledgement 
I acknowledge [ALTSchool Africa](AltSchoolAfrica.com) for the helpful instructors and resources as well as the online resources that has helped me during the learning process and doing this task 