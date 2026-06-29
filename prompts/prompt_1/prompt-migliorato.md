## Prompt Migliorato

```txt
Sei un developer esperto di [TECH_STACK]. 
Sistema la pagina dei ticket in [FILE_PATH].
Problemi da risolvere:
1. [PROBLEMA Specifico, es: layout rotto su mobile]
2. [PROBLEMA Specifico, es: manca filtro per stato]

Vincoli:
- Mantieni lo stile UI esistente
- Usa [LIBRERIA] per i componenti
- Compatibile con [BROWSER/DISPOSITIVO]

Output: codice completo della pagina con le correzioni applicate.

Esempio di fix atteso:
Input: il pulsante "Filtra" non si vede su schermi < 768px
Output: aggiunta media query con display:block e padding adeguato
```


## Strategia Del Prompt Finale

- Zero-shot o few-shot: few-shot
- Motivo della scelta: la risposta comprende degli esempi
- Se few-shot, cosa dimostrano gli esempi: che llm ha bisogno di capire su cosa deve lavorare
- Evidenze richieste all'AI: 
assunzioni: 
- Sei un developer esperto di [TECH_STACK]. 
criterio:
- Mantieni lo stile UI esistente
- Usa [LIBRERIA] per i componenti

verifica: non pervenuta



## Controllo Qualita'

- Contesto presente: si
- Confini espliciti: si
- Output atteso: si
- Prova di controllo: no
- Cosa chiede all'AI di non fare: 
   - Modificare lo stile UI esistente
   - Usa [LIBRERIA] per i componenti
- Esempi necessari e proporzionati:
   - Esempio di fix atteso:
   - Input: il pulsante "Filtra" non si vede su schermi < 768px
   - Output: aggiunta media query con display:block e padding adeguato
- Evita chain-of-thought estesa: no
- E' piu' specifico perche': ha un contesto, dei vincoli, un output atteso
- Limita meglio il lavoro perche': ha dei vincoli minimi
- Produce un output piu' verificabile perche': viene richiesto un output specifico
- Lo classificherei come: migliorabile
