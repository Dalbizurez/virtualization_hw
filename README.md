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
<img width="821" height="181" alt="successful ping to google.com" src="https://github.com/user-attachments/assets/20da3dca-858b-4ef6-ad40-ea772fe753ba" />

## IP Manual dentro de la misma subred
### Configuración
#### Netplan .yaml
<img width="827" height="219" alt="Netplan coniguration yaml file" src="https://github.com/user-attachments/assets/15628025-f240-4586-94f9-7c9c5ff3c42e" />

#### Resultado
<img width="959" height="702" alt="New IPv4 Address: 192.168.1.185; Subnet Mask: 255.255.255.0" src="https://github.com/user-attachments/assets/2fe351dd-fd70-4278-a449-391df766bd1b" />

### Ping a google.com
<img width="808" height="183" alt="successful ping to google.com" src="https://github.com/user-attachments/assets/53b178be-d854-4826-9762-ab479487c5f7" />

## IP manual fuera de la subred del hipervisor
### Configuración
#### Netplan .yaml
<img width="839" height="247" alt="Netplan coniguration yaml file" src="https://github.com/user-attachments/assets/5f7ef6d5-533f-482f-8bb8-bbb906b34bbd" />

#### Resultado
<img width="962" height="688" alt="image" src="https://github.com/user-attachments/assets/37ed579b-f427-45c9-8d2b-2e620a9cdccf" />

### Ping a google.com
<img width="816" height="180" alt="image" src="https://github.com/user-attachments/assets/471607fa-b0f4-4000-8129-79cd151bd06f" />
