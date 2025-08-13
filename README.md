 Practică anul 2 Calculatoare - Vara 2025
Partea scrisa a proiectului
Tema
Analiza problemei
Specificarea cerintelor
Proiectarea la nivel conceptual (Modelul conceptual al datelor / Diagrama Entitate Relatie)
Proiectarea la nivel logic (Modelul logic al datelor / Schema bazei de date relationale)
Proiectarea la nivel fizic (Modelul fizic al datelor)
Limbaje si librarii utilizate - o scurta descriere
Descrierea aplicatiei

Aplicatia Java va implementa interfata grafica in Java SWING si va folosi JDBC pentru conectarea la baza de date.

Pentru entitatile din aplicatie va permite cel putin:
    - listare/vizualizare
    - adaugare,
    - modificare,
    - stergere,
    - cautare,
    - filtrare
    - login

Suplimentar se pot implementa:
- export date in PDF/XLSX
- import date din XLSX
- rapoarte pentru o perioada selectabile si reprezentarea datelor sub forma une grafice (bar chart, line chart, pie chart)

Implementarea aplicatiei
- implementarea tabelelor in baza de date
- o aplicatie fara interfata grafica - de test - pentru utilizarea JDBC - testarea implementarii comenzilor SQL SELECT/INSERT/DELETE/UPDATE pe baza de date nou creata
- crearea interfetei grafice pentru aplicatia finala - Java SWING fie fara GUI Builder, de la 0, fie folosind un GUI Builder - de ex. NetBeans IDE GUI Builder, din WindowBuilder din Eclipse
- veti crea un singur JFrame pentru fereastra principala a aplicatiei si mai multe containere (de ex JPanel) pentru fiecare actiune/functionalitate si eventual ferestre de dialog (JDialog) unde este cazul. Aceste containere vor fi incarcate/afisate/ascunse/sterse in fereastra principala.
- implementarea sistemului de login
- afisarea functionalitatilor pe baza rolului fiecarui utilizator (fiecare utilizator va avea asociat un rol in aplicatie)
- implementarea functionalitatilor din capitolul "Specificarea cerintelor"
