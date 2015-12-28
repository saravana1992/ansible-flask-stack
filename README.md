Ansible Flask Stack
======================

Hello, this is an simple example of how to provision Vagrant Box with Ansible. 

Requirements
--------------
Make sure you have installed these dependencies:

- VirtualBox
- Vagrant
- Ansible

How To
--------
All environment variables are inside env_vars/base.yml

You have to specify desired flask repo address to *git_repo* variable.
Default is points to a [simple flask application](https://github.com/mehmettaskiner/flask-skeleton)

This project's structure is fairly simple. app.py must be in root folder in order to this work. 

    .
    ├── README.md
    ├── app.py
    └── requirements.txt



After you specify repo it takes just 2 words to spin up a webserver running specified flask app. 


    vagrant up

It takes 4-5 minutes to spin up server. 

After it completes, open up a browser then head to http://192.168.33.10