# hashcat-docker
Use Pre-Installed hashcat with Docker.

# Hashcat
Hashcat is a powerful tool that helps to crack password hashes. Hashcat supports most hashing algorithms and can work with a variety of attack modes. 

# Hashcat on Docker
I have created a docker image of hashcat on ubuntu base which can be used directly for cracking hashes and passwords by pulling the docker image and running it.

## Steps to use hashcat-docker:
1.) Pull the image of hashcat by using the following command:
    `docker pull homonomian/hashcat-docker`

2.) Once the image is downloaded you just need to run the hashcat with docker run command:
    `docker run -rm homonomian/hashcat-docker:v1 hashcat --help`
    
