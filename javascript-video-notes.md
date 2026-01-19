# Javascript - Videomuistiinpanot

## Video 1
- Nämä videot auttavat aloittelijoita oppimaan JavaScriptä
- Videosarjassa esintyy useita henkilöitä, jotka ovat kokeneita JavaScriptin kanssa

## Video 2
- JavaScript on ohjemloitni kieli, jota käytetään vuorovaikustukseen elementtien kanssa selaimessa
- JavaScript on yleisin käytetty ohjelmointi kieli, sillä voi luoda laadukkaita ja mnipuolisia sovelluksia ja nettisivuja

## Video 3
- JavaScript client viittaa verkkoselaimeen, silloin tarvitaan script tag jolloin JavaScript laitetaan sen sisälle
- JavaScript server on erilainen ja se on verkkkopalvelu, tähän tarvitaan Node.js jolla voi suorittaa JavaScript tiedoston kutsumalla Node:a
- Kolmannen osapuolen paketille on olemassa arkisto nimeltä npm, joka sisältää kaiken mitä voi vain ajatella. Esim. sellainen jolla voi laskea kuinka monta pizzaa tarvitaan riippuen kuinka monta ihmistä on

## Video 4
- JavaScriptin tekemiseen tarvitaan koodieditori (paras on VisualStudio Code) ja Node.js

## Video 5
- Windowsille on oma NVM sovellus, mikä on NVM-Windows, se on saman tyylinen kuin tuo toinen

## Video 6
- Asia jota tulet usein käyttämään on console.log command, se sallii sinun lähettää viestin konsoliin
- Kun halutaann kirjoittaa tekstiä käytetääm ' tai " (sillä ei ole väliä)
- Jos et tiedä arvoa niin voidaan käyttää subsitutions
- jos käyttää ´ se sallii sinun interpololoida tai yhdistää tekstiä ja ohjelmalliset arvot, kuten muuttujat

## Video 7
- Koodissa olevat kommentit voidaan merkitä kohtia ja niitä ei suoriteta koodissa
- Yhden rivin kommentit merkitään kahdella vinoviivalla // ja useamman rivin kommentit merkitään alkuun /* ja sitten loppuun */ kaikki siinä välissää muuttuu kommentiksi
- Tähän on olemassa pikanäppäimiä, mitkä ovat Windowsilla 
Ctrl + / ja jos haluaa useamman rivin niin sitten se kohta maalataan 

## Video 8
- Kommentit on hyödyllisiä eri käyttö tarkoituksissa, mutta koodiin ei kannata laittaa liikaa kommentteja, koska muuten siitä voi tulla sotkuinen ja sekavan näköinen

## Video 9
 - Muuttujien ilmoittaminen koodissa on kolme tapaa var, let ja const, joakainen näistä käytetään erilaisissa tilanteissa
 - var on muuttuja joka on käytettävissä vain sen funktion sisällä jossa se on määritelty ja sen voi uudelleenmäärittää
 - let on muuttuja joka näkyy vain sen lohkon sisällä jossa se on määritelty
 - const on muuttuja jonka arvo ei voi muutttaa sen jälkeen kun se on kerran asetettu

## Video 10
- Const on suositelluin käytettäväksi, koska se on luotettavampi ja lohkon sisäisen näkyvyyden vuoksi (Block Scope)

## Video 11
- JavaScriptissä Sting on merkkijono joka on tekstin esittämisen tietotyyppi
- String Concatenation voi kaksi ja useamman merkkijonon yhdistää pidemmäksi merkkijonoksi, plus operaattori (+) on yksinkertaisin tapa liittää kaksi jonoa toisiinsa

## Video 12
- Kun srtingien väliin kirjoittaa sanoja on hyvä jättää sanan loppuun välilyönti, muuten se tulostaa sanat yhteen

## Video 13
- Template Literals on JavaScriptin tapa käsitellä merkkijonoa, ne kirjoitetaan backtickien (`) sisään tavallisten lainausmerkkien sijasta
- Tällä voi suorittaa laskutoimtuksia tai kutsua funktiota suoraan ${} merkkien sisällä

## Video 14
- Template Literals tunnistaa näistä merkeistä ` `

## Video 15
- JavaScript on yksinkertaisemi ja joustavampi ohjelmointi kieli kuin mm. C# ja Java 
- Checking Type:ja on typeofjoka palauttaa merkkijonon jonka tietotyyppi on primitiivinen ja instanceof joka palauttaa totuusarvon jos arvo vastaa tietotyyppiä

## Video 16
- typeof operaattorille pitää olla varovainen koska se ei kykene erottamaan eri tyyppisiä objekteja toisistaan esim. listat (array)

## Video 17
- JavaScriptissä matematiikka tehdään perusoperaattoreilla (+, -. *, /)

## Video 18
- JavaScriptissä ++ merkki on inkermenttioperaattori joka kasvattaa muuttujan arvoa yhdellä
- merkki -- on dekrementtioperaattori joka vähentää muuttujan arvoa yhdellä 
- Näitä kahta tapaa käytetään ohjelmoinnissa jatkuvasti kun lukuja pitää päivittää automaattisesti

## Video 19
- Kun halutaan stringi muuttaa numeroksi käytetään joko parseInt() tätä käytetään kokonais numeroissa, parseFloat() tätä käytetään desimaali numeroissa
- Kun halutaan numero stringiksi käytetään toString()

## Video 20
- Jos parseInt() tai parseFloat() laitetaan kirjaimia se tulostaa NaN

## Video 21
- Throwing exceptions tarkoittaa ohjelman suorituksen keskeyttämistä hallitusti kun kohdataam odottamaton tilanne
- JavaScriprissä error:ja käsitellään try, catch ja finally näiden avulla ohjelma voi jatkaa toimintaansa

## Video 22
- logError eli virheen kirjaaminen tehtävänä on tallentaa tieto tapahtuneesta virheestä joko selaimen konsoliin, tiedostoon tai ulkoiseen palveluun

## Video 23
- Kun luodaan uusi päivämäärä objekti tehdään const now = new Date(), sitten määritellään vuosi, kuukausi ja päivä myös määritellään tunnit, minuutit ja sekunnit
- Kuukausien laskeminen alkaa 0:sta (tammikuu on 0)

## Video 24
- console.log(now); antaa meille UTC ajan, console.log(win95Launch); antaa meille ajan joka on aikaisemmin määritelty

## Video 25
- Kun katsotaan yhtäsuuria arvoja ja tietotyyppiä suositellaan käyttävän === 
- Kun katsotaan eriarvoisia arvoja ja tietotyyppiä suositellaan käyttävän tätä !==

## Video 26
- JavaScriptissä kun käytetään if tai else lausekkeita niin silloin ei tarvita {} mutta pitää olla varovainen koska se voi antaa virheellisiä tuloksia

## Video 27
- JavaScriptisä stringit ovat case sensitive eli ovat aian kirjainkoosta riippuvaisia, tämä tarkoittaa että vertyailut ja metodit huomioivat eron pienten ja suurten kirjainten välilä
- Switch -lauseketta käytetään suorittamaan eri koodilohkoja sen persutella mihin arvoon annettu öauseke täsmää (luotettavampi kuin if ja else ketjut), tätä käytetään kun verrataan yhtä muuttuujaa kiinteään arvoon

## Video 28
- toUpperCase -metodi muuttaatekstin isoiksi kirjiamiksi, koska stringit ovat muuttumattomia metodi ei muuta alkuperäistä tekstiä vaan palauttaa uuden merkkijononon
- Kaksi pystyviivaa (||) on looginen TAI-operaattori, sitä käytetään pääasiasa kahden arvon vertailuun tai oletusarvojen asettamiseen

## Video 29
- Array eli taulukko on lista tai arvojen kokoelma, jokaisella arvolla on indexi

## Video 30
- JacaScriptissä taulukon kokoa ei ole pakko määreitellän etukäteen ja se kasvaa automaattisesti siten kuin lisäät sinne tavaraa

## Video 31
- Array luomisen jälkeen siihen voi lisätä osoittamalla arvoja tiettyihin indekseihin, mikä ylikirjoittaa olemassa olevat arvot, ja kiinteänpituisen taulukoiden kohdalla pituuden seuraaminen on tärkeää

## Video 32
- Indeksejä käytetään tiettyjen arvojen löytämiseen ja käyttämiseen
- Taulukossa on tärkeää että siihen pystyy lisäämään arvoja

## Video 33
- array.push(values) lisää yhden tai useammman arvon taulukon loppuun ja palauttaa sen uuden pituuden, array.pop() poistaa yhden tai useamman arvon tauöukon alkuun ja palauttaa sen uuden pituuden

## Video 34
- array.shift() poistaa arvon tauöukon alusta ja palauttaa poistetun arvon, array.unshift(values) lisää yhden tai useamman arvon taulukon alkuun ja palauttaa sen uuden pituuden
- Concat yhdistää kaksi taulukkoa luodakseen uuden taulukon

## Video 35
- JavaScript looks (silmukat) ovat työkaluja joilla suoritettaan tiettyä koodilohjoa toistuvasti kunnes haluttu ehto täyttyy
- yleisiä loopeja on while, for, for ... of

## Video 36
- While loops on hyviä kun ei tiedeetä kuinka monta kertaa koodi on suoritettava, for loops käytetään kun tiedetään toistojen määrä, for ... of loops on moderni ja selkeä tapa käydä läpi iteroitavien kohteiden arvot

## Video 37
- 

## Video 38
- 

## Video 39
- 

## Video 40 
- 

## Video 41
- 

## Video 42
- 

## Video 43
- 

## Video 44
- 

