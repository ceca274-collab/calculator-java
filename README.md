# Calculator Java - Izveštaj o analizi koda

## 1. Softverska metrika: LOC (Lines of Code)
- Ukupan broj linija koda za projekat (Calculator.java fajl): 134 LOC (odnosno 188 ukupno sa praznim redovima)

## 2. Statička analiza koda i zapažanja
Format: `fajl – broj linije koda – zapažanje`

- Calculator.java – linija 6 – Korišćenje globalne statičke promenljive 'finalResult' umesto lokalnog stanja.
- Calculator.java – linija 61-65 – Hvatanje generičkog izuzetka (Exception) i vraćanje stringa "ERROR".
- Calculator.java – linija 74-188 – Metoda Calculate je predugačka (Long Method) i sadrži duplirani kod (Duplicated Code).
