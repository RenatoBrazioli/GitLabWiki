Criteri che devono essere considerati per poter inserire un _Work Item_ in uno Sprint.

I criteri devono essere soddisfatti al più tardi al momento dello Sprint Planning. In loro assenza, iniziare la lavorazione può implicare il rischio di non avere abbastanza informazioni, o risorse, a disposizione, e quindi di non essere in grado di completare il lavoro.

## Work Item Type: Software Item

### Descrizione

Descrizione sintetica, in termini di risultato che si vuole ottenere, più che elenco di "cose da fare" (queste possono essere specificate come checklist o come subtask).

Eventuali riferimenti a documentazione, altri _Work Item_ ecc. vanno esplicitamente collegati o inclusi come allegati.

#### User Story

Se il _Work Item_ ha come risultato la generazione di una interfaccia utente, usare la notazione User Story:

```
AS User
I WANT TO azione, ...
SO THAT motivo (valore che si genera)
```
#### Criteri d'Accettazione

I Criteri di Accettazione del _Work Item_ devono essere esplicitamente descritti usando la notazione:

```
GIVEN precondizioni
WHEN evento, azione, ...
THEN risultato atteso
```
### INVEST

In generale, considerare i criteri INVEST. Non devono necessariamente essere tutti soddisfatti, ma, quando assenti, danno una indicazione del livello di rischio che ci si sta assumendo.

#### **I**ndependent

Lo sviluppo del _Work Item_ deve avere il minimo numero possibile di dipendenze, sia interne (altri _Work Item_ in sviluppo) che esterne (input atteso da altri).

#### **N**egotiable

Le modalità di realizzazione tecniche del _Work Item_ devono essere il più possibile libere da decisioni prese al di fuori dell'ambito dello sviluppo.

#### **V**aluable

Il _Work Item_ genera valore, direttamente (funzionalità nuove o migliorata, correzione difetto), oppure indirettamente (refactoring, creazione infrastruttura). Un numero troppo elevato di _Work Item_ che generino valore di tipo indiretto sono, spesso, un sintomo di un lavoro non incrementale. 

#### **E**stimable

Il _Work Item_ deve essere compreso abbastanza da poter esprimere una valutazione sulla sua fattibilità.

#### **S**mall
Il _Work Item_ deve essere abbastanza "piccolo" da poter essere completato in uno Sprint.

#### **T**estable

Deve essere chiaro come si potrà testare il _Work Item_, sia per il soddisfacimento dei _Criteri d'Accettazione_ che per qualunque altro tipo di test (Unit, Integration, Non Regression, ecc.)

## Work Item Type: Knowledge Item

In generale, i criteri per un _Knowledge Item_ sono simili a quelli di _Software Item_, declinati in modo opportuno.


