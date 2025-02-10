# shutdown-programmato

Questo programma batch permette di spegnere un sistema Windows in modo programmato.

## Modi di esecuzione

### Manuale

1. **Esegui il programma manualmente**:
   - Fai clic destro sul programma `shutdown.bat` e seleziona **"Esegui come amministratore"**.
   
   **Attenzione:** Prima di eseguire il programma, assicurati di aver salvato tutti i lavori aperti!

### Programmato

1. **Crea un collegamento per eseguire il programma automaticamente**:
   - Fai clic destro sul programma `shutdown.bat` e seleziona **"Crea collegamento"**.
   - Fai clic destro sul collegamento creato, seleziona **Proprietà**, quindi clicca su **Avanzate** e spunta l'opzione **"Esegui come amministratore"**.
   
2. **Schedula l'esecuzione automatica**:
   - Cerca "Utilità di pianificazione" nella barra di ricerca di Windows e apri il programma.
   - Fai clic destro su **"Utilità di pianificazione (computer locale)"** e seleziona **"Crea attività di base"**.
   
3. **Imposta la pianificazione**:
   - Scegli quando programmare l'esecuzione (ad esempio, ogni giorno a un'ora specifica, ogni settimana con giorno e ora, ecc.).
   
4. **Imposta l'azione**:
   - Seleziona **"Avvia programma"** e scegli il collegamento creato al programma `shutdown.bat`.
