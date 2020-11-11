# LMP 2020
## Esercizio 01

Questo è il primo esercizio creato in Java per il corso di LMP.

# Changelog
Il changelog verrà aggiornato ogni qualvolta ci saranno modifiche nella struttura del codice

## Versione 0.2.0 - 11 Novembre 2020 (Thomas Mandija)
- Modifica progetto:
    - Creazione package:
        - `it.uniroma2.art.lmp.ex01`
        - `it.uniroma2.art.lmp.ex01.model`
        - `it.uniroma2.art.lmp.ex01.model.impl`
    - Spostamento file relativi package:
        - `it.uniroma2.art.lmp.ex01` -> `Runner.java`

        - `it.uniroma2.art.lmp.ex01.model` -> `Person.java`
        - `it.uniroma2.art.lmp.ex01.model` -> `Professore.java`
        - `it.uniroma2.art.lmp.ex01.model` -> `Studente.java`
        
        - `it.uniroma2.art.lmp.ex01.model.impl` -> `AngryStudent.java`
        - `it.uniroma2.art.lmp.ex01.model.impl` -> `PersonImpl.java`
        - `it.uniroma2.art.lmp.ex01.model.impl` -> `ProfessoreImpl.java`
        - `it.uniroma2.art.lmp.ex01.model.impl` -> `StudenteImpl.java`
- Modifiche file pre-esistenti:
    - `Person.java` -> aggiunta stringa `package`
    - `Runner.java` -> aggiunta stringa `package`, aggiunte stringhe `import`, modifiche nel main
    - PersonImpl.java -> aggiunta stringa `package`, aggiunta stringa `import`, modifica costruttore con ` this` 

## Versione 0.1.0 - 28 Ottobre 2020 (Fabrizio Perna)
- Creazione progetto
- Creati file:
    - `Person.java`
    - `PersonImpl.java`
    - `Runner.java`
- Descrizione file:
    - `Person.java`: file interface con metodi `getNome()`, `getCognome()`, `saluta()`
    - `PersonImpl.java`: file class con metodi `getNome()`, `getCognome()`, `saluta()`, `toString()` e costruttore `PersonImpl(nome_par, cognome_par)`
    - `Runner.java`: file classe con main, richiamo del costruttore, richiamo dei metodi