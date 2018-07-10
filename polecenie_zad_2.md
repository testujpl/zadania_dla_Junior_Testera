# Zadania_dla_Junior_Testera_Dzien_2


<img alt="Logo" src="https://testuj.pl/wp-content/uploads/2018/07/testujpl_logo.png">

Za Tobą pierwsze zadanie! 
Tematyka drugiego zadania w dalszym ciągu będzie dotyczyć tworzenia przypadków testowych. Tym razem zajmiemy się jednak kontrolą jakości oprogramowania. 

Zadanie 1. polegało na stworzeniu przypadku testowego sprawdzającego funkcję zakładania konta na GitHub. W tym zadaniu ponownie posłużymy się formularzem rejestracyjnym serwisu GitHub, ale skupimy się na sprawdzeniu poprawności walidacji pola *“hasło”*. 

# Zadanie do wykonania: 

Pole *“hasło”* w formularzu rejestracyjnym GitHub’a ma określone wymagania, które muszą zostać spełnione, aby rejestracja została przeprowadzona poprawnie (m.in. długość hasła, wielkość liter). Określ przypadki, które możesz utworzyć, aby sprawdzić czy wymagane kryteria rzeczywiście zostały spełnione. Następnie opisz je w taki sam sposób, jak przypadek testowy zgodnie z instrukcją podaną w zadaniu 1.

**WAŻNE!** Podczas walidacji pamiętaj o klasach równoważności i wartościach  brzegowych. 

___

> **Słowniczek**:

**Walidacja** - sprawdzenie, czy testowany produkt/moduł/pole spełnia kryteria i wymagania użytkownika lub klienta np. właściciela serwisu GitHub

**Klasy równoważności** - to podzbiór dziedziny danych wejściowych lub wyjściowych, dla którego zakłada się, na podstawie specyfikacji, że zachowanie modułu lub systemu jest takie samo. Co to oznacza?

Załóżmy, że testujemy pole w formularzu *„wiek”*. Klient w specyfikacji zaznaczył, że w tym polu powinny zawierać się liczby od 18 do 100 (oznacza to, że osoba, która chce zarejestrować się na portalu naszego klienta powinna mieć nie mniej niż 18 lat i nie więcej niż 100 lat). 

Mamy więc 3 klasy równoważności:
* < 18 
* 18 – 100
* >100

Reguła klas równoważności mówi nam, że wartości każdej z nich (klas) będą zachowywały się tak samo. To znaczy, że jeśli w polu *„wiek”* wpiszemy różne liczby mniejsze niż 18 lub różne liczby większe niż 100 to nie powinniśmy móc się zarejestrować. Jeśli  z kolei wpiszemy różne wartość z przedziału 18 -100 np. 72 i 23 – rejestracja powinna przejść pomyślnie. Innymi słowy, reguła równoważności mówi nam, że nie musimy testować wszystkich wartości w każdej z klas - wystarczy po jednej. :) 


**Wartość brzegowa** – wartość wejścia lub wyjścia, która jest na granicy klas równoważności lub jest w najbliższym przyrostowym sąsiedztwie tej granicy. Na przykład wartość minimalna lub maksymalna zakresu. Na podstawie powyższego przykładu naszymi wartościami brzegowymi mogą być liczby: 17, 18, 19 oraz 99, 100, 101. 

### Powodzenia!
