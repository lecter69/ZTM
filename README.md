<h1>Autorzy:</h1>

Jakub Martin,
Andrzej Rapita,
Piotr Rybsztad

<h1>Temat :Siłownia</h1>

ZTM jest serwisem związanym ze sportami siłowymi. Zawiera ciekawe informacje oraz porady, a także narzędzia ułatwiające przygotowanie do treningu oraz diety.

Serwis przeznaczony jest dla osób aktywnych, uprawiających sporty siłowe, początkujących, a także dla chętnych podjęcia treningu.

<hr/>

    Ustalenia na następne zajęcia xx.02.12:
    
    plany - układanie planu:
    - zapisywanie do bazy
    - wyświetlanie wszystkich planów
    - wyświetlanie pojednczego planu
    
<hr/>

<hr/>

    Ustalenia na następne zajęcia 20.01.12:
    
    plany - układanie planu - prototyp (widok):
    - tabela tygodniowa
    - przeciąganie i układanie planu
    
<hr/>

<h1>Sekcje:</h1>

<h2>Artykuły </h2>
<ul> 
    <li> Proste artykuły. Co sie działo w świecie, porady jakieś testy itp. </li>
    <li> Artykuł skłąda się z nagłówka, treści, autora, źródła, atrybut widocznosci (bool czy artykuł jest skończony i ma być widoczny dla wszystkich)i mozę należeć do wielu kategorii</li>
    <li> Powinny być w kategoriach.  np. eventy, dietetyczne, ćwiczenia itp. </li>
    <li> Do artykułu użytkownik zalogowany może dodać komentarz (Data dodania, jego ocena artykułu - tak jak na stronach helionu do książek )</li>
    <li> Ajax_rating do oceny - użytkownik może oceniać artykuł w widoku show, w showAll powinna byś statyczna ocena artykuły </li> 
    <li> Fajnie by było jakby artykuł miał spis treści powinien się sam generować np. tak jak na johnnybet.com </li>
    <li> Pod spodem powinny być linki do tematów powiązanych. </li>
</ul>

<h2>Sekcja Diety </h2>
<p>Użytkownik dzięki tej sekcji powienien mieć możliwosc ułożenia sobie diety na cały dzień. </p>


<ul>
    <li> Użytkownik określa liczbe posiłków wybiera produkty z naszej listy które są pogrupowane w kategorie. </li>
    <li> Powinna być baza danych produktów zaimportowana z jakiegoś pliku (nazwa, białko, węgle, tłuszcz itd..)  Użytkownik po wybraniu produkty określa ile gram chce go i stronka ma aktualizoać ajax'owo  ogólne podsumowanie, wyliczenie gramatury posiłku. coś w stylu <a href="http://www.optymal-btw.aktis.i.p.pl/kalkulator.html">kalkulator optymalny</a></li>
    <li> Jak nie ma produkty ma mieć mozliwośc dodać swój i ten produkt ma być widoczny tylko dla niej chyba że admin go zaakceptuje  do ogólnej widoczności </li>
    <li> Wybiera swoją wage, wiek, płeć jeżli nie podał w profilu albo edytuje to </li>
    <li> Potem klika wylicz i mu liczy ilość białka, węgli i tłuszczy w poszczególnych posiłkach no i w stosunku do masy na cały dzień według róznych współczynników i zakresów </li>
    <li> Ma mu tez wyliczyć jakie jest dla niego rekomendowane zapotrzebowanie ( jakieś wykresy itp.) i potem ma porównać jego wyniki z rekomendowanymi, i wyświetlać odpowiednie komunikaty // Martin: tutaj powinien być jakiś wybór, czy ma to być dieta na mase/redukcje, a dane do obliczeń musi pobierać z tabeli user, gzie mozna podac swoja wage i wzrost</li>
</ul>
<h2>  Sekcja ćwiczeń </h2>
    //napisze później 

<h2>  Userzy, css </h2>
<ul> 
    <li> Logowanie/rejestracja itd</li>
    <li> Panel użytkownika <br/>
        - Waga, wiek, wymiary biceps, klatka itd. wzrost,  emotka, id. <br/>
        - Jego dieta, jego plany treningowe, kalendarz ćwiczeń <br/>
    </li>
    <li>  CSS / Layout  - funkcjonalny i ładny </li>
    <li> Niezalogowany 
       <ol>
        <li>artyukuły widoczne, moze układac diete i plan terningowy ale nie lądują one w bazie tylko do druku</li>
        <li> Nie moze oceniać i komentować </li>
        <li> Jego produkty dodane i ćwiczenia nie powinny lądować do zaakceptowania dla admina tylko dla niego samego </li>
       </ol>
    </li>
    <li> Zalogowany
        <ol> 
        <li>Ma swój panel: swój profil (oczywiscie może edytować) ma swoje plany treningowe, diety może ulubione artykóły???</li>
        <li>Też widzi tylko artykuły, ćwiczenia ustawione na widoczne</li>
        <li>Moze zaproponowac swój produkt, ćwiczenie?  które jest widoczne tylko dla niego dopuki nie zaakceptuje tego admin/moderator</li>
        </ol>
    </li>
    <li> Autor czy tam writer - ogólny pisarz artykułów, ćwiczeń 
        <ol>
        <li>Może dodawać ćwiczenia, artykuły, partie ćwiczeń</li> 
        <li>Widzi na stronie niewidoczne artykuły, ćwiczenia - czyli te co mają widocznośc ustawioną na false</li> 
        <li>Może oczywiscie edytować artykuły i ćwiczenia </li> 
        <li></li> 
        </ol>
    </li>
    <li> Admin: Ma możliwość zaakceptowania produktu, dodane ćwiczenie, bany i pewnie coś wiecej ;P </li>
    
</ul>