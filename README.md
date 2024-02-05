# China-Unicom-vn009
todo lo que encontre sobre el modem china unicom vn009 (no lo voy a poner en ingles, existen traductores online etc)


1 - tenia el firmware 2.5.2 y lo actualice a 2.6.0 link: https://drive.google.com/file/d/1mFwEZvrswGBBJW-IEsehn1zKaN_3wiVz/view?usp=sharing




superuser password (adb) 

https://tool.zootu.cn/tools/api/007imei/

adb connect 192.168.21.1:5555
Login:superadmin
Password:lo que te dio la pagina de arriba (https://tool.zootu.cn/tools/api/007imei/)


login web como super usuario:
en la shell poner este comando

cat /tmp/mdlcfg.sysconfig | grep SYS_SENIOR_LOGIN_PWD

usuario: root
contraseña: la que da el comando de arriba

adios, no  he acmbiado imei ni nada, solo queria buscar el login root del modem y compartir como lo hice 👽
