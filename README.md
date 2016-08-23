# SFTP image

[![hope/sftp](https://img.shields.io/badge/docker-hope/sftp-brightgreen.svg)](https://hub.docker.com/r/hope/sftp/)

Easy to use SFTP (SSH File Transfer Protocol) server with OpenSSH

## Run

    docker run -p 2210:22 hope/sftp

### Enviroment variables
    
**SFTP_USER** – user name
**SFTP_PASS** – user password
**SFTP_HOME** – user home directory (for chroot)
