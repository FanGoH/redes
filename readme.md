# Pruebas de Red


## Red Derecha (LAN_1)

### Debian Principal

- NGINX
- Bind9
- Cuentas asr1, asr2. asr3

### Windows 7

Equipo de Administración

## Honeypots


### Honeypot 1 (10.21.1.101)

Tiene instalado Webmin, que es una interface de administracion sobre HTTP (root, admlnx@)

### Honeypot 2 (10.21.1.102)

Tiene instalado MySQL, puerto 3306 (root, password)

### Honeypot 3 (10.21.1.103)

Tiene tftp, una version *lightweight* de ftp, es mas insegura

### Debian con GUI (Atacante)

### Kali (Atacante)


### Firewall DO

Reglas Outbound
- TCP
  - HTTP
  - HTTPS
- UDP
  - DNS
  - NTP



## Red Izquierda (LAN_2)

### Debian Principal

- NGINX
- Bind9
- Cuentas asr1, asr2. asr3

### Windows 7

Equipo de Administración

## Honeypots


### Honeypot 1 (10.22.1.101)

Telnet server

### Honeypot 2 (10.22.1.102)

MongoDb

### Honeypot 3 (10.22.1.103)

Samba

### Debian con GUI (Atacante)

### Kali (Atacante)


### Firewall DO

Reglas Outbound
- TCP
  - HTTP
  - HTTPS
- UDP
  - DNS
  - NTP

