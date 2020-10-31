# docker-on-debian-using-playbook
Running docker container on multiple hosts using ansible-playbook scripts

Here's the order in which you should run them
  1. docker-install.yml
  2. docker-service.yml
  3. image-pull.yml
  4. run-container.yml
  5. copy-code.yml
