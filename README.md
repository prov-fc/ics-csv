# ics to csv

**Si consiglia di verificare il risultato facendo alcuni test**

**Testato con un export di Google Calendar**

Questa repo converte un file .ics in un file .csv, tenendo conto se un evento è ricorrente.

Sono state usate le seguenti librerie per lo sviluppo di questo programma:
- [**ical.js**](https://github.com/kewisch/ical.js): Per l'analisi del file ics
- [**luxon**](https://github.com/moment/luxon/): Per il calcolo delle timezones
- [**Papaparse**](https://github.com/mholt/PapaParse): Per la creazione del file csv
- [**PicoCSS**](https://github.com/picocss/pico): Per un minimo di stile