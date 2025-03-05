# Repository di prova

Questa è una repository di prova creata per testare la configurazione di un server web con Nginx e cloud-init.

## Contenuto della repository

- File di configurazione cloud-init per l'installazione e configurazione di Nginx.
- File HTML di esempio:
  - `Pippo.html`
  - `Pluto.html`
  - `index.html`

## Caratteristiche

- Installazione automatica di Nginx.
- Creazione di file HTML di esempio nella directory `/var/www/html/`.
- Configurazione di base del server web.

## Prerequisiti

- Sistema operativo supportato da cloud-init.
- Accesso a una macchina virtuale o istanza cloud.

## Utilizzo

1. Copia il file `cloud-init.yaml` nella tua macchina virtuale o istanza cloud.
2. Assicurati che Nginx sia installato e configurato correttamente.
3. Accedi alle pagine web tramite l'indirizzo IP della tua istanza:
   - `http://<indirizzo-ip>/index.html` per la pagina principale.
   - `http://<indirizzo-ip>/Pippo.html` per la pagina di Pippo.
   - `http://<indirizzo-ip>/Pluto.html` per la pagina di Pluto.

## Note

- Questa repository è puramente dimostrativa e non deve essere utilizzata in un ambiente di produzione senza ulteriori modifiche e personalizzazioni.
- Assicurati di configurare correttamente i gruppi di sicurezza e le autorizzazioni secondo le tue necessità.
