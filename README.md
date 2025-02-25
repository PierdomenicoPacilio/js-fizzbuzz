# Esercizio: FizzBuzz
Scrivi un programma che stampi i numeri da 1 a 100,
ma per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi Buzz.
Per i numeri che sono sia multipli di 3 che di 5 stampi FizzBuzz.
---
### Prima prova :
#### passaggi:
##### inizializzazione delle variabili e creazione del ciclo :
- Creare il ciclo con il seguente indice (i = 1; i <= 100; i++)
    - SE i % 3 === 0 
        - scrivere Fizz
    - SE i % 5 === 0
        - scrivere Buzz
    - ALTRIMENTI
        - scrivere i
###### pensavo che mi scrivesse semplicemtente Fizz e Buzz uno dopo l'altro attaccati, invece andavano a capo
---
### Seconda prova :
#### passaggi:
##### inizializzazione delle variabili e creazione del ciclo :
- Creare il ciclo con il seguente indice (i = 1; i <= 100; i++)
    ##### essendo un ordine a cascata descriviamo prima il caso FizzBuzz, ovvero dove entrabe le condizioni di divisibilità (3 e 5) vengono confermate :
    - SE (i % 3 === 0 && i % 5 === 0)
        - scrivere FizzBuzz
    ##### poi successivamente Fizz e Buzz separati
    - SE (i % 3 === 0)
        - scrivere Fizz
    - Se (i % 5 === 0)
        - scrivere Buzz
    ##### infine per tutti gli altri numeri scrivere semplicemente la variabile i
    - ALTRIMENTI
        - scrivere i
###### aggiungendo un pasaggio più specifico prima degli altri evito che quelli dopo vengano processati e l'output è corretto
---