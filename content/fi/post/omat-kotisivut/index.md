---
title: "Omat kotisivut tutkijalle"
subtitle:

# Summary for listings and search engines
summary: Mihin tutkija tarvitsee omat kotisivut? Tässä blogitekstissä esitän siihen kaksi itseäni motivoivaa perustetta ja kerron samalla omasta kotisivuprojektistani.

# Link this post with a project
projects: []

# Date published
date: "2020-12-19T00:00:00Z"

# Date updated
lastmod: "2020-12-19T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement:
  preview_only: false

authors:
- admin

tags: ["kotisivut"]

categories: ["tutkimusviestintä"]

copyright_license:
  enable: true
  allow_derivatives: true
  share_alike: true
  allow_commercial: true
  notice: ''

---

Tässä blogitekstissä esitän kaksi itseäni motivoivaa perustetta omien kotisivujen tekemiseen ja kerron omasta kotisivuprojektistani.

## Miksi omat kotisivut?

Perinteisten "tutkijan näkyvyys" ja "verkostoituminen" lisäksi voi ottaa huomioon seuraavat perusteet: 

Ensinnäkin tutkijan on usein mahdollista julkaista painettua versiota edeltävä versio (Accepted Manuscript) omilla henkilökohtaisilla kotisivuillaan[^1]. Esimerkiksi kotiyliopiston tietokantoihin tai tutkijoiden sosiaaliseen mediaan (kuten Academia tai ResearchGate) julkaisemisen esteenä on usein kaupallisten kustantajien asettama viive (embargo).

Toiseksi tutkijan koti-instituutio voi nykyisin vaihtua usein. Työsopimuksen päätyttyä myös yliopiston ylläpitämät omat sivut tutkijalle sekä tiedot julkaisuista voivat kadota. Hyvät kotisivut mahdollistavat sen, ettei omien tietojen ja julkaisujen löytäminen ole muille työlästä.

## Oma kotisivuprojekti

Omat kotisivut voi tehdä monella alustalla ja ehkä helpoin työkalu niiden tekemiseen on Wordpressin kaupallinen versio. Tämä sivusto ei kuitenkaan toimi Wordpressin päällä, vaan [Hugon](https://gohugo.io). Tämän teknologian päälle on rakennettu tutkijoille selkeät ja hienot sivut mahdollistava [Academic/Resume Starter](https://wowchemy.com/templates/) -kotisivupohja. Muutama peruste tälle valinnalle:

- Sivut ovat nopeat ja responsiiviset.
- Staattisten sivujen vuoksi tietoturvariskit ovat pienet (vrt. Wordpress).
- Sivustopohja ja sitä pyörittävä palvelin on ilmainen[^2]. Tämän sivuston suhteen maksan ainoastaan domainista (n. 10 euroa vuodessa). Sivuston lähdekoodi sijaitsee [GitHubissa](https://github.com) ja se pyörii [Netlify-palvelussa](https://www.netlify.com).
- Sivusto ei kerää yksilöllistä tietoa sen kävijöistä (Google Analytics on kuitenkin mahdollista asentaa, mutta tällöin pitää muistaa GDPR-asiat).
- Sivusto mahdollistaa julkaisujen tallentamisen [Zoteron](https://www.zotero.org) kautta.
- Sivustopohja on suunniteltu tutkijoille.
- Sivustopohjalla on hyvä SEO (löytyy siis hyvin Googlesta).
- Sivusto on helppo varmuuskopioida (vrt. Wordpress).

Muutama peruste vastaan:

- Sivuston tekeminen ja ylläpitäminen vaatii hieman opettelua[^3]. Vaikka sivustopohjan ohjeistus lupaa kotisivun tulevan valmiiksi 10 minuutissa, niin silti kaikenlaiseen säätämiseen kuluu aikaa. Sivuston lähdekoodia tulee muokkailla, ratkaisuja täytyy etsiä googlesta ja sivuston näkyvyyteen tulee nähdä hieman vaivaa. Myös sivuston julkaisujärjestelmä vaatii todennäköisesti uusien ohjelmien opettelua.

{{% callout note %}}
Huom. 20.2.21 Sivustoa voi nykyisin editoida myös selaimen kautta. Lue [täältä](https://wowchemy.com/docs/getting-started/cms/) lisää. Se helpottanee säätämistä.
{{% /callout %}}

Kannattaa alkuun selata sivuston ohjeita [täältä](https://wowchemy.com/docs/getting-started/install/). Lisäksi voit tutustua [sivustoni lähdekoodiin](https://github.com/vesvalim/vesvalim). Näistä saa hieman kuvaa, mitä sivuston tekeminen vaatii.
## Haasteita

- Netlify hoitaa SSL-sertifikaatin ja DNS-asiat (näissä tuli hieman ongelmia). Oman domainpalvelun kautta laitoin ainoastaan CNAME-ohjauksen tämän sivuston Netlify osoitteeseen.
- En pitänyt sivuston Faviconista (se kuva mikä näkyy sivupalkissa). Sen vaihtaminen onnistui helposti em. sivuston ohjeiden avulla. Oman faviconin voi tehdä esimerkiksi [tämän sivuston](https://gauger.io/fonticon/) kautta.
- Sivuston monikielisyys vaatii hieman enemmän nikkarointia, mutta lopputulokseen olen oikein tyytyväinen. Lue lisää sivuston monikielisyyden asentamisesta [täältä](https://wowchemy.com/docs/guide/language/).

[^1]: Google Scholar myös useimmiten löytää tämän pdf-version tutkijan kotisivuilta ja yhdistää sen varsinaiseen artikkeliin. Tässä menee kuitenkin hieman aikaa. Esimerkiksi [tässä artikkelissa](https://scholar.google.com/scholar?hl=fi&as_sdt=0%2C5&q=links+between+v%C3%A4lim%C3%A4ki&btnG=) meni noin kaksi viikkoa linkin päivittymiseen.

[^2]: [Ilmainen tiettyihin rajoihin saakka](https://www.netlify.com/pricing/). Netlify-palvelulla on omat kaistarajoituksensa (100GB/kk), joten hyvin suosittua sivustoa se ei ilmaiseksi pyöritä. Tutkijan sivusto kuitenkin todennäköisesti.

[^3]: Apua sivuston käyttämiseen on kuitenkin saatavilla. Esimerkiksi sen yksityiskohtaisista [asennusohjeista](https://wowchemy.com/docs) tai sen Discord-yhteisöstä.