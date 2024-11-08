# shutdown-programmato

Programma batch per lo spegnimento di windows

modi di eseguirlo:
- manuale ---> click destro sul programma shutdown.bat e click su "esegui come amministratore"
!!! ATTENZIONE, PRIMA DI ESEGUIRE IL PROGRAMMA ASSICURARSI DI AVER SALVATO EVENTUALI LAVORI !!!

- programmato:

  {
     - click destro sul programma shutdown.bat e click su "crea collegamento"
     - click destro sul collegamento, click su proprietà e click su avanzate per spuntare "esegui come amministratore"
     - aprire "utilità di pianificazione", click destro su "Utilità di pianificazione (computer locale)" e poi "crea attività di base"
     - inserire quando schedularlo (ogni giornoc+  ora, ogni settimana + giorno e ora, ecc)
     - inserire azione ovvero l'avvio del programma e scegliere il collegamento del programma
  }
