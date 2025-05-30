# Filologia Forense
## _Laboratorio 17/04/2025 Chieti_

Da questi file illegibili trovare tramite analisi dell’esadecimale quante più informazioni possibili

## Istruzioni
- Aprire un editor esadecimale online. Es. [HexEd](https://hexed.it/)
- Scaricare uno o più file dal repository
- Il file può essere trascinato direttamente nell'editor esadecimale
- Provare a cercare informazioni utili 

## Consigli di metodo
- Ricercare header
- Identificare il tipo di file
- Rinominarlo aggiungendo l'estensione corretta
- Provare a datarlo facendo ricerche su internet
- Controllare ulteriori informazioni nascoste dopo la stringa di chiusura (metadati, parole chiave, informazioni personali residue, font, testo cancellato ecc.)


## Lista header
_✨Magic bytes_
- **FE 37 00 23** = Word 5.0 per Macintosh → estensione= .mcw
- **FE 37 00 1C** = Word 4.0 → estensione= .mcw
- **FE 34 00 1C** = Word 3 → estensione= .mcw
- **D0 CF 11 E0** = Word 97-2003 → estensione= .doc
- **31 BE 00 00 00 AB** = MS Word 4.0/PC file → estensione =.doc
- **FF D8 FF** = File immagine → estensione =.jpeg

## Stringa di fine testo
**75 00** → stringa di fine testo. Il materiale dopo è stato cancellato o aggiunto dopo la chiusura

## Emulatore
Si può provare a vedere i file in un emulatore scaricando il software da [Qui](https://we.tl/t-PXCYHjzBTh)

# Link utili 
- [Lista versioni word](https://it.wikipedia.org/wiki/Microsoft_Word)
- [Editor esadecimale online](https://hexed.it/)
  



