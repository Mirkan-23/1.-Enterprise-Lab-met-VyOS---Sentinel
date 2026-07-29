# DH-APP-01

DH-APP-01 is bedoeld als een applicatie/fileserver binnen de netwerk. Op deze server draait een Samba SMB fileshare voor interne gebruikers.

## Systeeminformatie

- Hostname: dh-app-01
- OS: Rocky Linux
- IP-adres: 172.16.25.41

## Services
Samba | SMB fileshare voor Windows clients

## Installatie

1. Samba pakket installeren (Op Rocky 9: dnf install samba)
2. smb.conf plaatsen in /etc/samba/
3. Gebruiker toevoegen
4. Service starten
5. Firewall SMB toestaan