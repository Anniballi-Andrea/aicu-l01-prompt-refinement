## Diagnosi Operativa

- Informazioni mancanti: tool di sviluppo, modifiche effettivamente necessarie alla pagina
- Ambiguita': la parola sistema è molto vaga, e non si va al punto su cosa va sistemato
- Rischio di scope troppo largo: si
- Output non verificabile: si
- Strategia iniziale: non chiara
- Servono esempi? Si  perche': non c'è un riferimento a cosa va sistemato

## Prompt Usato Per Migliorare

```txt
Aiutami a migliorare questo prompt.
Non risolvere il task.
Dimmi prima quali informazioni mancano.
Indica se basta una versione zero-shot o se servono 1-2 esempi few-shot.
Non mostrare chain-of-thought estesa: elenca solo assunzioni, criterio e verifica proposta.
Poi proponi una versione migliore.
```

## Strategia Del Prompt Finale

- Zero-shot o few-shot: zero-shot
- Motivo della scelta: Non servono esempi perché il modello deve solo analizzare il caso
- Se few-shot, cosa dimostrano gli esempi:
- Evidenze richieste all'AI: assunzioni: mostrare un messaggio e difinire delle azioni / criterio  / verifica