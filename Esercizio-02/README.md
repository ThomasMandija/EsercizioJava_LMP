# LMP 2020
## Esercozop 02

Questo è il secondo esercizio creato in Java per il corso di LMP.

# Changelog
Il changelog verrà aggiornato ogni qualvolta ci saranno modifiche nella struttura del codice

## Versione 0.1.0 - 18 Novembre 2020 (Marco Altomare)
- Creazione progetto
- Creati file:
    - `PersonImpl.java`
    - `ProfessoreImpl.java`
    - `StudenteImpl.java`
    - `Cdl.java`
    - `Person.java`
    - `Professore.java`
    - `Studente.java`
    - `Runner.java`
- Descrizione file:
    - `PersonImpl.java`: file `class` con metodi `getNome()`, `getCognome()`, `saluta()`, `toString()` e costruttore `PersonImpl(nome_par, cognome_par)`
    - `ProfessoreImpl.java`: file `class` con metodi `getCorso()`, `setCorso()` e costruttore `ProfessoreImpl(nome, cognome, corso)`
    - `StudenteImpl.java`: file `class` con metodi `getMatricola()`, `toString()`, `saluta(Professore p)`, `saluta(Professore p, String appellativo)` e costruttore `StudenteImpl(nome, cognome, corso)`
    - `Cdl.java`: file `enum` con metodi `getCodice()`
    - `Person.java`: file `interface` con metodi `getNome()`, `getCognome()`, `saluta()`
    - `Professore.java`: file `interface` con metodi `getCorso()` e `setCorso()`
    - `Studente.java`: file `interface` con metodi `getMatricola()`, `saluta(Professore p)` e `saluta(Professore p, String appellativo)`
    - `Runner.java`: file `class` con main, richiamo del costruttore, richiamo dei metodi