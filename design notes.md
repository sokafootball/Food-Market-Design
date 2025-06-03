
# Food Market

I giocatori sono chef di ristoranti di lusso che competono per avere gli ingredienti sul mercato per realizzare i propri piatti

## Keywords
- **P**: Numero di giocatori (max 4)
- **I**: Numero di tipi di ingredienti: **5**
- **MI**: Massimo numero di ingredienti che un giocatore può avere nel frigo (davanti a sè): **7**
- **FI**: Numero di ingredienti che si può mettere in freezer, e quindi conservabili tra un turno e l'altro: **1**
- **CI**: Massimo numero di ingredienti dello stesso tipo che si possono prendere dal mercato in un unico turno: **3**
- **X**: Numero da definire
- **Ricetta 1/2/3**: Ricetta da 1/2/3 punti
- **Costo 3/2/1**: La ricetta richiede 3 di un ingrediente, 2 di un secondo tipo e 1 di un terzo tipo
- **Costo 3/2-2/1**: La ricetta richiede per il secondo ingrediente 2 di un tipo o in alternativa 2 di un altro

## Materiali

- Per ogni giocatore **I** token di un colore corrispondente con numeri che vanno da 1 a **I** di dimensione crescente. 
- **P** carte cuoco di colori diversi, che rappresentano ogni giocatore
- Token ingredienti (quanti per tipo???)
    - Pesce
    - Carne
    - Grano
    - Verdura
    - Formaggio
- X carte mercato
- X carte ricetta con all'interno
    - punteggio
    - immagine e titolo
    - ingredienti richiesti

## Preparazione
- Dare una carta cuoco ad ogni giocatore
- Dare i token acquisto ad ogni giocatore del colore corrispondente
- Preparare le pile di ingredienti in mezzo al tavolo
- Preparare il mazzo mercato in mezzo al tavolo


## Fase 1 (Fase Mercato)

- Vengono distribuite ad ogni giocatore 3 carte ricetta che vengono messe davanti a lui scoperte
- Viene girata 1 carta mercato e messa in mezzo ai giocatori. Questa carta detta quanti ingredienti ci sono per ogni tipo
- Viene girata una carta evento che applicherà degli effetti per questo giorno
- Partendo dal primo giocatore, ogni giocatore mette un token su uno degli ingredienti, non si può ripetere lo stesso numero sullo stesso ingrediente.
- Quando tutti i token sono messi, l’ultimo giocatore decide da quale ingrediente partire. 
- In ordine di token più alto i giocatori prendono da 1 a **CI** di quegli ingredienti. In qualsiasi momento un giocatore non può avere più di **MI** ingredienti davanti a sè. Non è possibile in questa fase eliminare ingredienti per fare spazio ad altri.
- Se non ci sono più ingredienti di quel tipo, o se il giocatore col token più basso (1) ha finito di comprare, si tolgono gli ingredienti di quel tipo rimasto e si passa all’ingrediente successivo.
- Quando questa fase è finita per tutti gli ingredienti, parte la fase 2

## Fase 2 (Fase Cucina)

- Ogni giocatore mette da parte nella sua area le ricette completate, scartando dal proprio frigo gli ingredienti usati. Inoltre vanno scartate tutte le ricette non completate tranne una scelta dal giocatore.
- Tutti gli ingredienti non utilizzati vanno rimessi nella pila di ingredienti corrispondente. Il giocatore può tenere **FI** ingredienti se lo desidera tra un turno e l'altro.
- Si ricomincia la FASE 1, questa volta il primo giocatore è quello che ha scartato meno ingredienti nella Fase 2 appena conclusa. In caso di parità il primo giocatore è quello con meno punti. In caso di parità il primo giocatore è quello con meno ricette completate. In caso di parità è il giocatore più giovane.
- Il gioco si conclude se alla fine della FASE 2 non ci sono più carte mercato da girare. Vince il giocatore che ha + punti.


## Idee e Ragionamenti

### Ingredienti sul mercato / **MI** / **CI**

il numero di ingredienti disponibili per un tipo, relazionato al costo delle ricette e ai valori di **MI** e **CI** dovrebbe avere un minimo ed un massimo (o un fisso?) in grado di creare situazioni interessanti.

#### Chi ha una chance di completare una ricetta per ogni categoria in base al numero di giocatori?

2 giocatori:
- ricetta 1: tutti i giocatori
- ricetta 2: primo giocatore, secondo giocatore + freezer
- ricetta 3: primo giocatore + freezer

3 giocatori:
- ricetta 1: tutti i giocatori
- ricetta 2: primo giocatore, secondo giocatore + freezer
- ricetta 3: primo giocatore

4 giocatori:
- ricetta 1: tutti i giocatori
- ricetta 2: primo giocatore, secondo giocatore, terzo + freezer
- ricetta 3: primo giocatore o secondo con ingrediente in freezer

Quindi se una ricetta 3 ha un ingrediente di cui ne servono 4 dello stesso tipo, il numero massimo di quell'ingrediente nel mercato deve essere:

2 giocatori: 3
3 giocatori: 4
4 giocatori: 5

### Carte ricetta

#### Punti

- 1 punto
- 2 punti
- 3 punti

#### Costo

- si può bilanciare il punteggio della carta in questi modi
    - dare più di una opzione per completare la ricetta (- punti)
    - Richiedere più ingredienti dello stesso tipo (+ punti) (facile da counterare da altri giocatori)
- 1 punto: possibile cucinare anche 2 in un giorno, quindi costo non maggiore di **MI** / 2
    - 1/1/1
    - 2-2/1
- 2 punti: possibile cucinarlo insieme ad una ricetta 1, ma difficile con altro 2 e impossibile con un 3
    - 2/1/1
    - 2/2
    - 3-3/1
- 3 punti: 
    - 3/2/1 
    - 2/2/1/1
    - 4-4/2

### Altro

- *set*: possibilità di completare dei *set* di ricette, che danno punti extra, in modo da creare situazioni in cui il giocatore può completare sia una carta da pochi punti che una da tanti ma non entrambe, e rendere più appetibile la carta da poco in alcune situazioni. O comunque non rendere scontata la scelta del giocatore. Set per nazionalità?
    - Non rendono i punti della ricetta l'unico criterio di valutazione di scelta di quale ricetta fare
- *carte obiettivo*: come strumento per simile al set per non rendere ovvie alcune decisioni dei giocatori al momento di puntare una ricetta piuttosto che un'altra, sono carte che il giocatore pesca a inizio partita e che permettono di fare più punti se soddisfatti.
    - creano informazioni nascoste e un elemento di sorpresa fino a fine partita
    - Non rendono i punti della ricetta l'unico criterio di valutazione di scelta di quale ricetta fare
- *carte evento*: carte che entrano in gioco subito dopo che i giocatori hanno svelato il mercato del giorno e hanno pescato le loro carte ricetta
    - creano maggiore interazione tra giocatori
    - esempi:
        - Ogni giocatore passa al giocare alla destra /sinistra una carta ricetta
        - Carte che aiutano il giocatore con meno punti (es. il giocatore prende un ingrediente a scelta dal mercato)
- *abilità cuoco*: ogni carta cuoco aggiunge una capacità, es. freezer più capiente, possibilità di avere 4 carte ricetta, possibilità di tenere 2 ricette, fare più punti coi set, ecc.
    - serve a rendere il gioco più vario tra una partita e l'altra
- *segnalini spreco*: ogni volta che un giocatore scarta un ingrediente pesca un segnalino spreco, ogni X segnalini spreco fanno perdere 1 punto a fine partita
    - rendono più interessante la scelta di counterare un avversario e non rendere banale la decisione di prendere tutto il possibile