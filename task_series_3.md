# Tehtäväsarja 3
## Backend ja tietokannat

### Keskustelupalsta

* **1 A** Lisää tietokantaan `posts` taulu:

![1A](./images/Screenshot1.png)

* **1 B** Lisää `posts` tauluun viiteavain postaukseen itseensä: `parent_post_id -> id`:

![1B](./images/Screenshot2.png)

* **1 C** Lisää tauluun vielä uusi kenttä (column), josta voisi olla hyötyä tällaisessa keskustelupalstan viestin datassa, esim. title tai topic. Lisätty title kenttä. Varchar koska voidaan olettaa otsikko tiettyyn pituuteen sekä määritetty pakolliseksi kentäksi.

![1C](./images/Screenshot3.png)

* **2 A** Lisää tietokantaan viesti.

![2A](./images/Screenshot4.png)

* **2 B** Lisää tietokantaan myös toinen viesti, tällä kertaa vastausviesti missä `parent_post_id`:ssä on aiemmin lisäämäsi aloitusviestin `id`:

![2B](./images/Screenshot5.png)

* **2 C** Millä tavalla saat haettua tietokannasta kaikki viestit jotka ovat aloitusviestejä?
![2C](./images/Screenshot6.png)

* **2 D** Miten saat haettua yksittäisen aloitusviestin id:n perusteella myös kaikki vastaukset kyseiseen aloitusviestiin yhdellä tietokantakyselyllä?
![2D](./images/Screenshot7.png)


