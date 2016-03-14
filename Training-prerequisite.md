### Training Prerequisite

Without revealing too many details at this point, participants in the training will go through the steps involved in running and developing a simple voting app from a fresh computer using Docker Toolbox and Compose. This simple app will include:

- A Python webapp which lets you vote between several options
- A Redis queue which collects new votes
- A Java worker which consumes votes and stores them in…
- …A Postgres database backed by a Docker volume
- A Node.js webapp which shows the results of the voting in real timedocker-toolbox

There will be a self-paced beginners’ tutorial for attendees to learn Docker basics as they build and deploy this app locally. Experienced Docker users will serve as mentors to help beginners successfully complete the training.

At the training, you will need to bring your own computer. Before you go to a birthday party training, there are some steps you should do some preparation to get your work environment ready. Here are the steps:

1. Create github account.     
  For this training, you will require to access github repo.
  Also, as part of challenge, you will be making PR to docker Birthday App repository.

  Incase you don't have github account, please create one https://github.com/join

  In case you are not familiar with github.
  Github self training:
  - https://try.github.io/levels/1/challenges/1
  - https://training.github.com/kit/courses/github-for-developers.html


2. Laptop:

    Should run 64 bit Operating system with capablity of running VirtualBox.
    


3. Softwares:

- For Linux users, we need you to install [Docker engine] (https://docs.docker.com/engine/installation/)
- For PC and Mac users we need you to install [Docker toolbox for Mac and Windows](https://www.docker.com/products/docker-toolbox) and use [Docker Machine] (https://docs.docker.com/machine/get-started/) to create a virtual machine to run your Docker containers. Once your machine is created and you have connected your shell to this new machine, you're ready to run Docker commands on this host.  If you're using Linux you can skip to the next step.
- If you're new to Docker, pre-pull the docker images for the very basic tutorial

   ```bash
   docker pull hello-world
   docker pull busybox
   docker pull seqvence/static-site
```
- To run the application and participate in the rest of the training, pre-pull these images

   ```bash
   docker pull node:0.10
   docker pull python:2.7-alpine
   docker pull java:7
   docker pull redis:alpine
   docker pull postgres:9.4
   ```
And now you're ready. See you at the birthday party!

<a href="https://www.docker.com/docker-birthday"><img align="right" src="https://www.docker.com/sites/default/files/illustration-com-container-party.png"></a>

```
```


NOTE: In case you have already docker installed on your machine, please check docker version must be 1.10+.

In case you face any trouble, feel free discuss [here](https://github.com/docker-meetup-tokyo/dockerbday-training/issues/new)
