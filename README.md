To ping all servers. Specify the `-k` option for password-based auth. If not, copy the keys over via `ssh-deploy-key`.

    $ ansible slaves -m ping -k

Taken from https://www.digitalocean.com/community/tutorials/how-to-deploy-a-basic-php-application-using-ansible-on-ubuntu-14-04

ansible php -m ping

ansible-playbook php.yml --ask-sudo-pass

https://medium.com/@tedchength/installing-docker-using-ansible-script-c182787f2fa1
