# Modos de red VMS
## Configuración inicial
### Subred del hipervisor
<img width="966" height="242" alt="IPv4 Address: 192.168.1.103; Subnet Mask: 255.255.255.0" src="https://github.com/user-attachments/assets/eb7677c3-5e44-47a2-a23b-c16515d640ca" />

### Adaptador en modo Bridge
<img width="975" height="647" alt="Configuración de adaptador en modo bridge" src="https://github.com/user-attachments/assets/0b0f7606-50bd-4e11-8fc5-9c86c645fb9a" />

#### Cambio de Hostname
<img width="894" height="145" alt="image" src="https://github.com/user-attachments/assets/a1d0ab0c-d0f1-42a9-9efb-90d064475760" />

## IP automática por DHCP
### Configuración
<img width="1037" height="672" alt="IPv4 Address: 192.168.1.152; Subnet Mask: 255.255.255.0" src="https://github.com/user-attachments/assets/68c5a1eb-e3b4-4383-9721-97102e288b97" />

### Ping a google.com
<img width="732" height="177" alt="successful ping to google.com" src="https://github.com/user-attachments/assets/4eaaea05-528d-4cfb-89b1-0a21c88fb5e6" />


## IP Manual dentro de la misma subred
### Configuración
#### Netplan .yaml
<img width="868" height="327" alt="image" src="https://github.com/user-attachments/assets/f8e07a64-d691-4d11-b141-251e755a45a0" />


#### Resultado
<img width="957" height="701" alt="image" src="https://github.com/user-attachments/assets/5c241ac3-f2f0-4553-8eaa-60b4b055df0e" />

### Ping a google.com
<img width="728" height="182" alt="image" src="https://github.com/user-attachments/assets/a5e609fd-52a1-41e3-b145-daaf0ce1dc52" />


## IP manual fuera de la subred del hipervisor
### Configuración
#### Netplan .yaml
<img width="859" height="331" alt="image" src="https://github.com/user-attachments/assets/038ad7fa-506f-4f24-8345-274a4d1cbdbc" />

#### Resultado
<img width="958" height="705" alt="image" src="https://github.com/user-attachments/assets/70904f71-fac2-459a-ab53-017e356a235b" />

### Ping a google.com
<img width="700" height="184" alt="unsuccessful ping to google" src="https://github.com/user-attachments/assets/fed145f7-ea6e-47e6-a0a1-f7229f0fa09f" />
