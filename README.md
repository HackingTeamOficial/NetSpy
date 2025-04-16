Herramienta hecha en Python para mostrar información detallada de una dirección IP
Herramienta hecha en Python para mostrar información detallada de una dirección IP. 

Cuando queremos expandir los resultados después de ingresar a la intranet, primero podemos saber a qué segmentos de intranet puede acceder al anfitrión.

NetSpy es un gadget creado por una aplicación. Es de tamaño pequeño y es extremadamente rápido, admite la plataforma cruzada y admite la detección de protocolo múltiple. ¡Espero que pueda ayudarte!
🚀 Uso rápido

Ver información de ayuda

netspy -h

Use el módulo ICMPSPY para la detección

La detección automática se realiza utilizando el módulo ICMPSPY, y los segmentos de red de detección automática son: "192.168.0.0/16", "172.16.0.0/12", "10.0.0.0/8".

Netspy es

Nota: Puede intentar usar el módulo PingSpy cuando no tiene permiso para enviar el paquete ICMP.

Use el módulo Arpspy para la detección

Especifica usar la interfaz de red ETH0 para la detección del protocolo ARP, y los segmentos de la red de detección son 192.168.0.0/16 y 59.192.0.0/10.

netspy -c 192.168.0.0/16 -c 59.192.0.0/10 como -i eth0

Use el módulo TCPSPY para la detección

netspy ts -p 22 -p 3389

Nota: Si no se especifica el parámetro -p, NetSpy predeterminado a los puertos de sonda 21, 22, 23, 80, 135, 139, 443, 445, 3389, 8080.

Use el módulo UDPSPY para la detección

Netspy US -P 53 -P 137

Nota: Si no se especifica el parámetro -p, NetSpy predeterminado a los puertos de sonda 53, 123, 137, 161, 520, 523, 1645, 1701, 1900, 5353.

Use el módulo ICMPSPY para forzar toda la detección de supervivencia de IP dentro del segmento

netspy -c 192.168.91.0/24 -r 255 -f es

Use el módulo ICMPSPY para detectar rápidamente el modo

netspy -x es

Nota: El número de coroutinas en el modo rápido es los núcleos de CPU * 40, y solo se detectan las puertas de enlace dentro del segmento.

Happy Hacking 

Nuestras RRSS

Telegram

https://t.me/+YWhDjkfmSQ9jY2Jk

https://t.me/+74d-97oV7P05OTVk

https://t.me/+llcmNGzz6JIyMmI0

https://t.me/PlantillasNucleiHackingTeam

https://t.me/TermuxHackingTeam

https://t.me/+-RIgaFP12_RhNTk0

X

@HackingTeam777

Bluesky

https://bsky.app/profile/hackingteam.bsky.social

Discord

https://discord.gg/V4nPFbQX

Facebook

https://www.facebook.com/groups/hackingteam2022/?ref=share https://www.facebook.com/groups/HackingTeamCyber/?ref=share

Youtube

https://www.youtube.com/@HackingTeamOfficial

Canal de tiktok

https://www.tiktok.com/@hacking.kdea?_t=ZS-8vTtlaQrDTL&_r=1

#hackingteam #cibersecurity #infosec #eticalhacking #pentesting #dns #script #cracking #hack #security #bugbounty 
#payload #tools #exploit #cors #sqli #ssrf #python #c2 #poc #web #ramsomware #phishing #linux #osint #linux #windows 
#redteam #blueteam #spyware #digitalforensics #reverseengineeringtools #rat #malwareforensics #exploitdevelopment 
#sandboxing #apt #zerodayexploit #xss #github #cve #java #tools #termux #troyano #dev #sqlmap #waybackurls #copilot 
#ai #ia #kalilinux #parrot #dracos #susse #nessus #oswazap #burpsuite #wireguard #redes #ciberseguridad #ciberseguridadespaña 
#informatica #python #scripting #pythonscripting
