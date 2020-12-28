[![GitHub license](https://img.shields.io/github/license/GiuseppeDiPalma/Fast-Configure-Server-First-Time?style=plastic)](https://github.com/GiuseppeDiPalma/Fast-Configure-Server-First-Time/blob/main/LICENSE?style=plastic)![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/GiuseppeDiPalma/Fast-Configure-Server-First-Time?style=plastic)![GitHub commit activity](https://img.shields.io/github/commit-activity/m/GiuseppeDiPalma/Fast-Configure-Server-First-Time?style=plastic)

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
