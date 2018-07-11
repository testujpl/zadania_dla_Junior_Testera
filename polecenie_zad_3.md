# Zadania_dla_Junior_Testera_Dzien_3
<img alt="Logo" src="https://testuj.pl/wp-content/uploads/2018/07/testujpl_logo.png">


Może się zdarzyć, że jako Junior Tester dostaniesz do przetestowania system gdzie będzie dużo zależności logicznych. 

Wyobraźcie sobie, że w sklepie internetowym w panelu administratora macie 2 rodzaje kont o różnych uprawnieniach:
* **Konto 1: Właściciel** - może dodawać, usuwać, produkty lub zmieniać ceny.
* **Konto 2: Sprzedawca** - może dodawać i usuwać produkty, ale tylko jeśli jest zalogowany na firmowym komputerze. Sprzedawca nie może zmieniać cen produktów.  


W takiej sytuacji mamy kilka zależności, które należy przetestować. Przy projektowaniu przypadków testowych pomocna może być tablica decyzyjna.

Tablica decyzyjna to jedna z czarnoskrzynkowych technik testowania (czyli takich gdzie nie zaglądamy w kod ;) Jest ona bardzo pomocna do zapisywania reguł biznesowych (warunków), które zawierają zależności logiczne. Warunki wejściowe i zachowanie systemu zapisujemy sobie jako kombinację prawdy i fałszu. 

W powyższym przykładzie (2 kont o różnych uprawnieniach) tablica mogłaby wyglądać następująco:

>T - prawda

>F - fałsz



<img src="https://testuj.pl/wp-content/uploads/2018/07/zad-3.png">

Zauważ, że w warunkach nie dodaliśmy opcji: *“jest właścicielem”*. Domyślnie założyliśmy, że jeśli nie jest sprzedawcą to jest właścicielem :) 

Wykorzystując tablicę decyzyjną łatwiej uchwycić nam kombinacje warunków, które należy sprawdzić. 


Teraz kolej na Ciebie!

# Polecenie zadania: 

Wyobraź sobie, że jesteś testerem w firmie wytwarzającej oprogramowanie na potrzeby portów lotniczych, a dokładniej kas sklepów wolnocłowych. 
W sklepie wolnocłowym zakupu może dokonać jedynie osoba posiadająca bilet. Pasażerowie, którzy chcą zakupić alkohol muszą mieć ukończone 18 lat. 
Jeżeli pasażer leci poza kraje Unii Europejskiej otrzymuje rabat na alkohol w wysokości 30%. 

Stwórz tablicę decyzyjną, która pomoże Ci w zaprojektowaniu przypadków testowych. 

### Powodzenia!
