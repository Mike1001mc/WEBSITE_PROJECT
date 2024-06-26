# WEBSITE_PROJECT
WORK GROUP SU GITHUB - CREAZIONE PAGINA WEB 
## Descrizione

Questo progetto è un sito web creato da un team di quattro persone. Ogni membro del team ha lavorato su una parte specifica del sito: header_part1, content_part2, content_part3 e footer_part4. Abbiamo utilizzato Git e GitHub per gestire il nostro lavoro collaborativo, creando branch separati per ciascuna parte del sito e facendo il merge dei branch nel branch principale.

## Istruzioni per il Setup

1. Clona questo repository:
    ```bash
    git clone https://github.com/Mike1001mc/WEBSITE_PROJECT.git
    cd website-project
    ```

2. Ogni membro del team deve lavorare sul proprio branch:
    ```bash
    git checkout -b <nome-del-branch>
    ```

    I branch creati sono:
    - `header_part1`
    - `content_part2`
    - `content_part3`
    - `footer_part4`
 3. Si aggiungono, committano e pushano le modifiche:
    ```bash
    git add .
    git commit -m "Descrizione delle modifiche"
    git push origin <nome-del-branch>
    ```
## Unione dei Branch

Una volta che tutte le parti sono state completate, il project manager unirà i branch nel branch `main`:

1. Si fa il checkout al branch principale:
    ```bash
    git checkout main
    ```

2. Si unisce ciascun branch:
    ```bash
    git merge header_part1
    git merge content_part2
    git merge content_part3
    git merge footer_part4
    ```

3. Si pushano le modifiche nel branch `main` su GitHub:
    ```bash
    git push origin main
    ```

    ## Risoluzione dei Conflitti

Durante il merge potrebbero esserci conflitti. Questi conflitti vanno risolti manualmente, poi bisogna aggiungere e committare le modifiche risolte:
    ```bash
    git add .
    git commit -m "Risolti conflitti"
    git push origin main
    ```
## Collaboratori
    - `header_part1` - [Marius]
    - `content_part2` - [Paul]
    - `content_part3` - [Francesco]
    - `footer_part4` - [Eduardo]
