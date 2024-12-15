---
Title: MÄTVÄRDE
Description: This is our mätvärde page.
---




Studie om laddningstid
=======================


Urval
-----------------------
Jag har valt att analysera följande tre webbplatser:

Amazon.se  en stor e-handelsplattform.
Ikea.com en global möbelbutik med en omfattande webbplats.
Aftonbladet.se en populär svensk nyhetssida.

Dessa webbplatser valdes för att representera olika typer av innehåll: e-handel, detaljhandel och nyheter. De är också mycket besökta, vilket gör det intressant att undersöka deras prestanda och användbarhet.

Metod
-----------------------

För att samla in data använde jag följande verktyg:

Google Pagespeed Insights för att mäta prestandabetyg för både mobil och desktop.
Webbläsarens Developer Tools (DevTools) fliken "Network" användes för att mäta laddningstid, antal resurser och total storlek.
Google Sheets för att dokumentera alla mätvärden.
För varje webbplats valdes tre sidor som analyserades. Varje sida mättes tre gånger, och ett genomsnitt beräknades. 


Resultat
-----------------------


<h2>AMAZON</h2>
<img src="../assets/img/amazon.png" alt="Amazon" width="600">

<p>Valda sidor:</p>
<p>Startsidan (amazon.se)</p>
<p>Produktkategori (amazon.se/smartphones)</p>
<p>Produktdetaljsida (amazon.se/product)</p>

<p>Pagespeed Betyg:</p>
<p>Mobile: 72</p>
<p>Desktop: 88</p>

<p>DevTools (genomsnitt):</p>
<p>Laddningstid: 3.5 sekunder</p>
<p>Antal resurser: 120</p>
<p>Total storlek: 2.6 MB</p>

<p>Förbättringsförslag: Optimera bildstorlekar och minska tredjepartsresurser.</p>

<h2>IKEA</h2>
<img src="../assets/img/ikea.png" alt="Ikea" width="600">

<p>Valda sidor:</p>

<p>Startsidan (ikea.com)</p>
<p>Produktkategori (ikea.com/kitchen)</p>
<p>Produktdetaljsida (ikea.com/product)</p>

<p>Pagespeed Betyg:</p>

<p>Mobile: 65</p>
<p>Desktop: 81</p>

<p>DevTools (genomsnitt):</p>

<p>Laddningstid: 4.3 sekunder</p>
<p>Antal resurser: 135</p>
<p>Total storlek: 3.4 MB</p>

<p>Förbättringsförslag: Implementera caching och minska JavaScript-filer.</p>

<h2>AFTONBLADET</h2>
<img src="../assets/img/aftonbladet.png" alt="Aftonbladet" width="600">

<p>Valda sidor:</p>

<p>Startsidan (aftonbladet.se)</p>
<p>Nyhetsartikel (aftonbladet.se/article)</p>
<p>Sport (aftonbladet.se/sport)</p>

<p>Pagespeed Betyg:</p>

<p>Mobile: 58</p>
<p>Desktop: 76</p>

<p>DevTools (genomsnitt):</p>

<p>Laddningstid: 5.2 sekunder</p>
<p>Antal resurser: 160</p>
<p>Total storlek: 4.2 MB</p>

<p>Förbättringsförslag: Optimera annonser och minska antalet resurser.</p>



Analys
-----------------------

Vanliga förbättringsåtgärder: De flesta webbplatser kan förbättras genom att optimera bilder, minska antalet resurser och implementera effektiv caching.
Rangordning av webbplatser:

<p>Amazon.se – Relativt snabb laddningstid och hanterbart antal resurser.</p>
<p>Ikea.com – Bra prestanda men något långsammare än Amazon.</p>
<p>Aftonbladet.se – Långsam laddningstid och hög resursförbrukning påverkar betyget.</p>

Vinnare: Amazon.se är vinnaren tack vare dess snabba laddningstid och väloptimerade resurser.


Jag anser att en snabb webbplats bör ladda på under 1 sekund, medan en långsam laddar på över 1 sekund. Baserat på mina tester laddar alla tre webbplatserna snabbt och håller sig nära eller under denna gräns. Amazon.se upplevs som den snabbaste och mest responsiva webbplatsen, medan Ikea.com och Aftonbladet.se laddar något långsammare men fortfarande inom en acceptabel tidsram. Generellt sett känns alla tre webbplatserna snabba och användarvänliga, vilket ger en positiv användarupplevelse.

<h2>Rådata från mätningar</h2>
<div class="video-container">
    <iframe 
        src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRCQbg1LrDEOBzChh_Q3iXGoWS1OsNOmdxHcS-S_xMdEVcUwXHAq_NOq87d0RBlyHYGBT8lk0leuQmx/pubhtml?widget=true&amp;headers=false" 
        title="Min favoritvideo" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</div>



Övrigt
-----------------------

Författare: Hussein Sabte