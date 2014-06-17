# {API:Suomi} palvelu

Osoite: http://apisuomi.fi

{API:Suomi} palvelu **listaa Suomessa käytössä olevat rajapinnat**. Käyttäjät voivat arvostella ja kommentoida palveluun ilmoitettuja rajapintoja. 

Lisäksi käyttäjät voivat ehdottaa lisättäviä rajapintoja. **Rajapintojen sovellutuksista kertovat "sotatarinat"** tuovat oman lisänsä ja innostavat muita kehittäjiä. 

Tämän lisäksi palvelussa listataan **API tapahtumia**, jotka voivat olla yksinkertaisia lounastapaamisia (API lounas) tai muutaman päivän mittaisia kattavia konferensseja (ei vielä Suomessa yhtään). 

## Rajapinnan lisääminen palveluun

* Tällä hetkellä rajapinnan lisääminen onnistuu vain lisäämällä "tuote" valikoimaan manuaalisesti. 
* Tavoite on saada aikaiseksi koneellinen (API) tapa lukea sisään rajapintojen tietoja esim github repositoryssä sijaitsevasta manifest (JSON) tiedostosta. 
* Jotta tiedetään mistä repoista pitää etsiä, tarvitaan listaus repositoreista, tyyliin https://github.com/kyyberi/apisuomi/blob/master/apirepositories.json
* Kehityksessä oleva esimerkkisyntaksi apimanifest.json tiedostosta löytyy täältä https://gist.github.com/kyyberi/48b6560947e16a5a587a

* Lisäksi yksi tapa olisi syöttää kyseinen manifest (JSON) apisuomi.fi palveluun tiedostona web käyttöliittymän kautta kuten apis.io palvelussa http://apis.io/apis/add 
