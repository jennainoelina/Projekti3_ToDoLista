# Projektin nimi ja tekijät
Projektin "Tehtävälista" tekijänä Jenna Vahviala

## Verkkolinkit:
Pääset julkaistuun sovellukseen käsiksi osoitteessa https://tehtavalistajv.netlify.app/

Linkki projektin videoesittelyyn https://fotovahviala.kuvat.fi/kuvat/Omat/LAUREA/Websovellusten+kehitt%C3%A4minen/

## Työn jakautuminen 
Koko projektin teki Jenna Vahviala.

## Oma arvio työstä ja oman osaamisen kehittymisestä
Mielestäni onnistuin ulkoasussa. Koen tumman värin olevan itselleni mukavampi näissä sovelluksissa. Sain ulkoasusta myös modernin ja yksinkertaisen näköisen ilman, että näyttää kuitenkaan tylsältä.
Sovelluksesta jäi puuttumaan aikarajoitus. Voisi pystyä laittamaan päivämäärän, jolloin pitäisi olla valmis. Tällä hetkellä päivämäärä on vain lisäysajalle ja se on kk/pv/vv muodossa.
Tuntui, että näiden ulkoisten kirjastojen hyödyntäminen oli juuri se puuttuva osaaminen tällaisten sovellusten luomiseen. Nyt tuntuu, että kykenee soveltamaan oppimaansa suhteellisen hyvin.

Antaisin itselleni arvosanaksi: 5

## Palaute opettajalle kurssista sekä itse opetuksesta tähän saakka
Kurssi sekä lähiopetus ovat tuntuneet todella hyödyllisiltä. Workshopit ovat auttaneet tehtävien ymmärtämisessä kun apua on saatavilla helposti. Tehtävissä käytettiin paljon opittuja koodeja, mutta myös sellaisia pätkiä ja rakenteita, joita ei mielestäni käyty yhteisesti läpi tai selitetty ollenkaan. Oppimista tukisi huomattavasti koodien läpikäynti ja selitys, mitä yksittäiset koodit tekee. Jouduin itse kysymään tekoälyltä paljon apua koodien selittämisessä, koska teorioissa ei käyty asiaa läpi tarpeeksi perusteellisesti.

Mutta yleisesti ottaen nautin kyllä tästä kurssista, tehtävistä ja opetuksesta. Pidän Mikan opetustyylistä.

Tämän viimeisen projektin tekeminen tuntui haastavammalta, kuin aikaisempien. Tuntui uuvuttavalta jälleen "aloittaa alusta" luominen näin lyhyen ajan sisään. 


## Sisällysluettelo:

- [Tietoja sovelluksesta](#tietoja-sovelluksesta)
- [Tunnetut virheet/bugit](#Tunnetut-virheet/bugit)
- [Kuvakaappaukset](#kuvakaappaukset)
- [Teknologiat](#teknologiat)
- [Asennus](#asennus)
- [Kiitokset](#kiitokset)

## Tietoja sovelluksesta
Tehtävälista on yksinkertainen ja selkeä sovellus päivittäisten tehtävien hallintaan.
Sovelluksessa voi:

- lisätä tehtäviä
- valita tehtävän prioriteetin (matala, keskitaso, korkea)
- merkitä tehtäviä valmiiksi
- poistaa tehtäviä
- käyttää suodatusnappeja (kaikki, valmiit, keskeneräiset)
- nähdä tehtävän lisäämishetken päivämäärän
- säilyttää tehtävät localStoragessa, jolloin ne eivät katoa sivun sulkeutuessa
- Tehtävät käyttäytyvät myös visuaalisesti erilailla:
- valmiit tehtävät harmaantuvat ja pienenevät hieman
- prioriteetit näkyvät eri väreillä

## Tunnetut virheet/bugit
Tehtävät eivät ole järjestettävissä vedä-ja-pudota -tyylillä (potentiaalista jatkokehitystä). Tunnettuja bugeja ei oikein syntynyt projektin luomisen aikana.

## Kuvakaappaukset
[ESIM1](./kuvat/SS1.png)
[ESIM2](./kuvat/SS2.png)
[ESIM3](./kuvat/SS3.png)
[ESIM4](./kuvat/SS4.png)

## Teknologiat
Käytin seuraavia teknologioita sovelluksen rakentamiseen:

- HTML
- CSS
- JavaScript
- jQuery
- SweetAlert2
- localStorage
- Tailwind (CDN)

Koodi tehtiin Visual Studio Code -editorissa. Demovideo ja julkaistu sovellus ovat internetissä.

## Asennus 
1. Sovellus löytyy osoitteesta https://tehtavalistajv.netlify.app/
2. Kirjoita tehtävä tekstikenttään.
3. Valitse prioriteetti.
4. Paina Lisää tehtävä.
5. Voit merkitä tehtävän valmiiksi, poistaa sen tai suodattaa listausta.
6. Tehtävät tallentuvat localStorageen automaattisesti.

## Kiitokset  
- AI (ChatGPT)
- Canvas materiaali
- Mika Stenberg opetus
- W3schools (https://www.w3schools.com/)

AI toimi apuna koodipätkien ja vikojen etsimisessä. Auttoi myös koodien soveltamisessa oikeaan tarkoitukseen.
