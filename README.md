https://img.shields.io/github/license/GiuseppeDiPalma/Fast-Configure-Server-First-Time?style=plastic

# [FCSFT]Fast configure server first time

Uno script utile per configurare rapidamente un server al primo uso.

## Requisiti necessari

- Sicurezza;
- Rapidità;
- No software aggiuntivi;
- Non costituire intralcio a lavori futuri sul server.

## Task utili

- [] Update iniziale
- [] Deve ritornare info necessarie in ambito IT riguardo alla macchina
  - [] Hostname
  - [] Versione SO
  - [] Ip interno
  - [] Ip esterno
  - [] Porte Aperte
  - [] Utenti creati e attivi
  - [] Info hardware macchina
  - [] Data ultimo update
  - [] Versione servzi installati
- [] Generazione chiavi accesso ssh
  - [] Gestione chiavi
- [] Rimozione accesso ssh con password a root
- [] Gestione firewalling iniziale
- [] Installazione e configurazione servizio ntp

Un semplice bash che configura un server(Ubuntu|CentOS|OracleLinux) al primo avvio. Cambiare questa.

### Come eseguire

```bash
https://raw.githubusercontent.com/GiuseppeDiPalma/Fast-Configure-Server-First-Time/main/configure.sh | bash
```
