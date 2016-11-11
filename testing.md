I propose to use this procedure:

https://www.ansible.com/blog/testing-ansible-roles-with-docker

Please see the travis file in https://github.com/openearth-stack/postgresql/blob/master/.travis.yml as an example.



# Test setup

Git clone repositories:
```
 git clone https://github.com/openearth-stack/postgresql.git
 git clone https://github.com/openearth-stack/general.git
```

 ## install docker
```
 sudo apt-get update
 sudo apt-get install docker.io
```

# How to run travis yml locallly
 http://stackoverflow.com/questions/21053657/how-to-run-travis-ci-locally

lid worden van de dockergroep
```
vigr
docker:x:117:tester
vigr -s
```
# open new terminal

select an image from Quay.io. If you're not using a language-specific image pick travis-ruby. Open a terminal and start an interactive Docker session using the image URL:
```
docker run -it quay.io/travisci/travis-ruby /bin/bash
```
