## Esegui lo script

--- task ---

Digita il seguente comando nel terminale e premi <kbd>Invio</kbd> per eseguire lo script:

```bash
./run_sd.sh
```

--- /task ---

--- task ---

Ti verrà chiesto di inserire un prompt. Si tratta di una descrizione dell’immagine che desideri generare. Il prompt guida il processo di generazione dell’immagine descrivendo la scena o l’oggetto desiderato. Se vuoi saperne di più su come scrivere un buon prompt per un generatore di immagini con l'intelligenza artificiale, [dai un’occhiata al progetto qui]{:target="_blank"}.

```bash
Inserisci il prompt: Un gatto
```

Premi <kbd>Invio</kbd>.

--- /task ---

--- task ---

Quindi, inserisci il numero di passaggi. Questo parametro influisce sulla qualità dell’immagine. In generale, un numero maggiore di passaggi produce immagini di qualità superiore, perché il modello ha più opportunità per perfezionare il risultato. Su un Raspberry Pi 5 con 4GB di RAM, ogni passaggio richiede circa 1 minuto.

```bash
Inserisci il numero di passaggi: 5
```

Premi <kbd>Invio</kbd>.

--- /task ---

--- task ---

Inserisci il nome del file immagine. Questo è il nome con cui verrà salvata l'immagine generata.

```bash
Inserisci il nome con cui salvare l'immagine generata: gatto.png
```

Premi <kbd>Invio</kbd>.

--- /task ---

--- task ---

Attendi che l'immagine venga generata.

Lo script verrà ora eseguito utilizzando i tuoi parametri per generare l’immagine. Questo processo può richiedere alcuni minuti, a seconda del numero di passaggi e delle prestazioni del tuo computer.

--- /task ---

--- task ---

Controlla l'output.

Una volta completato il processo, l’immagine generata verrà salvata nella corrente cartella con il nome file specificato.

![Un gattino arancione e bianco con grandi occhi espressivi e un nasino rosa sdraiato su una superficie di legno accanto a dei rametti di lavanda. Il gattino ha un fiocco rosa intorno al collo. Sullo sfondo ci sono rametti di lavanda e un mazzo di fiori di lavanda avvolto in tela grezza, su uno sfondo rosa tenue.](images/cat.jpg)

--- /task ---

Seguendo questi passaggi, puoi facilmente generare immagini utilizzando lo script. Il prompt definisce il contenuto dell’immagine, il numero di passi ne influenza la qualità e il nome stabilisce come verrà chiamato il file una volta salvato.

Divertiti a creare le tue immagini!
