
Techniki służące do dynamicznej zmiany treści, wyglądu lub zachowania się doku. mentu HTML umożliwiają interakcję użytkownika ze stroną internetową. W skład dynamicznego HTML wchodzą technologie: DOM, CSS, HTML, SVG, języki skryptowe

(JavaScript, VBScript i inne). DOM (ang Document Object Model) to sposób reprezentacji dokumentów XML i HTML w postaci modelu obiektowego Jest on niezależny od platformy i języka programo wania. Standard zdefiniowany dla DOM przez organizację W3C opiera się na zespole klas i interfejsów. Za ich pomocą możliwy jest dostęp do struktury dokumentu oraz możliwa jest jego modyfikacja. Standard W3C definiuje interfejsy DOM tylko dla jezyków JavaScript i Java.

SVG (ang. Scalable Vector Graphics) to uniwersalny format grafiki wektorowej (statycznej i dynamicznej) stworzony z myślą o zastosowaniu na stronach internetowych. Może bye integrowany z językami opartymi na technologii XML. Zostal opracowany przez organizację W3C na potrzeby internetu. W SVG oprócz standardowych obiektów (pro stokątów, elips, krzywych) można opisywać efekty specjalne, maski przezroczystości oraz sposób animacji elementów.

Języki skryptowe to języki interpretowane, zaprojektowane z myślą o interakcji z użytkownikiem. Skrypty są wykonywane wewnątrz określonej aplikacji w odróżnieniu od programów nieskryptowych, które wykonują się niezależnie od innych aplikacji.

Język skryptowy działający po stronie przeglądarki jest najważniejszym elementem dynamicznego HTML


JavaScript jest obiektowym skryptowym językiem programowania nawiązującym do języka C. Jest językiem interpretowanym, co oznacza, że efekty jego użycia można zobaczyć bez konieczności kompilowania kodu. Potrzebna jest tylko przeglądarka internetowa, która obsluguje język JavaScript. Tworzone skrypty zapewniają interak tywność strony internetowej poprzez reagowanie na zdarzenia, budowanie elementów nawigacji oraz sprawdzanie poprawności formularzy


Typowe zastosowania języka JavaScript to:

-modyfikowanie wyglądu bieżącego dokumentu, wyświetlanie prostych okien dialogowych
-kontrola poprawności wypełnienia formularza,
-manipulowanie informacją dotyczącą dary i czasu,
-lokalne generowanie dokumentów HTML




===============================================================================
CSS-model blokowy
hierarchicznie:

1.Margin - margines wokół ramki(zewnetrzny)
2.border - obramowanie wokół elementu, ma styl i kolor
3.padding - odstęp między obramowaniem a zawartośćią elementu(margines wewnętrzny)
4.content - zawartość elementu np. text czy obrazy
↑
powyższe atrybuty tworzą układ graficzny

Do zmiany szerokosci obramowania służy atrybut BORDER-WIDTH
selektor(border-width:wartość/i)
1 wartość oznacza tą samą szerokosc i wysokość
2 wartośći oznaczają 2 osobne wartosci dla szerokosci i wysokośći(poziom,pion)
mozna tez skalować poszczególne krawędzie np. BORDER-BOTTOM-WIDTH:wartość lub np. BORDER-TOP-WIDTH:wartość
a takze stylowac obramowanie dzieki BORDER-STYLE:wartość lub BORDER-BOTTOM-STYLE czy też BORDER-TOP-STYLE
