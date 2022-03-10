# PEzor-Docker <img src="https://upload.wikimedia.org/wikipedia/commons/7/79/Docker_%28container_engine%29_logo.png" width=250 height=40>
<img src="https://img.shields.io/badge/Docker-Image-blue">     <img src="https://img.shields.io/badge/PEzor-Packer-blueviolet">

With the help of this kali linux image, you can easily access PEzor on your system! 

Basically, this image is built from the kalilinux/kali-rolling image and then the PEzor shellcode and PE packer is installed on top of it. Sometimes, it's vital to have access to PEzor, specially in a post exploit phase, but installing it on a host or a VM is a time-consuming task due to the dependencies that are required. Having said that, this docker image is created to solve this problem and provide a quick way to access PEzor.


P.S. All the credits for the wonderful PEzor tool are reserved for [@phra]( https://github.com/phra ) .

# Disclaimer
This docker image is only for educational purposes and ethical uses! Any misuse of this image is totally on your own risk. 

# About PEzor
With the help of this incredible tool, you can create FUD malwares that are capable of bypassing most of the well-known AVs. 
For instance, you can pack the "mimikatz" executable file with the help of PEzor and then run it against victim's system for a full mem dump without any problem! 😎

# How to use
*<b> NOTE: You need to have docker installed on your system. </b>*

```
docker pull https://hub.docker.com/r/4d0niis/pezor_included_kali:1.0
```
```
docker run -it 4d0niis/pezor_included_kali:1.0 /bin/bash
```
```
PEzor <COMMANDS>
```

<img src="https://raw.githubusercontent.com/4D0niiS/PEzor-Docker/main/PEzor_docker.png?token=GHSAT0AAAAAABSJNQCE2IVME72JKYJYXYGOYRI2I5Q">


# References
https://hub.docker.com/r/4d0niis/pezor_included_kali

https://github.com/phra/PEzor

https://hub.docker.com/r/kalilinux/kali-rolling



