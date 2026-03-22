# Agent Rules — sum-check-protocol

> Questo protocollo viene spesso utilizzato per verificare somme o integrità di dati tra un prover e un verifier. Qui faremo una versione molto semplificata: il client proverà di conoscere dei numeri che sommano a un certo valore senza rivelarli direttamente.

## Codice
- Nomi descrittivi, no abbreviazioni crittiche
- Docstring su ogni funzione pubblica
- Type hints in Python, Javadoc in Java
- Nessun magic number senza costante nominata

## Testing
- Unit test obbligatori per ogni funzione pubblica
- Nessuna modifica senza test di regressione

## Sicurezza
- Zero segreti nel codice — usa variabili d'ambiente
- Nessuna chiave API, password o token in chiaro

## Git
- Conventional Commits: feat:, fix:, docs:, refactor:, test:, chore:
- Commit atomici, un concetto per commit
- Nessun file generato o .env nel repository

## Lingua
- Commenti e docstring in italiano
- Messaggi di commit in inglese
