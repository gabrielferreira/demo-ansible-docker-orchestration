# demo-ansible-docker-orchestration
First you need to clone the project
```sh
$ git clone git@github.com:gabrielferreira/demo-ansible-docker-orchestration.git
$ cd demo-ansible-docker-orchestration
```
execute the command bellow to install Docker at the destination Host
```sh
$ ansible-playbook -i hosts install-docker.yml
```
execute the command bellow to build and run the Docker container
```sh
$ ansible-playbook -i hosts docker-image.yml
```

Now open your browser and enter the Docker URL **http://HOST_URL**

**It's Done**
