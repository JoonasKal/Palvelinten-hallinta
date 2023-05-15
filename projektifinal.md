Tämä on kurssin viimeinen tehtävä. Tarkoituksena on kurssilla opittuja taitoja hyödyntäen tehdä projekti omien taitojen mukaan.
Päätin opetella kuinka terminalin avulla saa avattua selaimeen omia sivuja.

Ensimmäiseksi päätin kokeilla asentaa apachen ja kokeilla sen avulla saanko näkymään apache2 kotisivun selaimeen.
Annoin komennon "sudo apt install apache2" ja asensin apache2 koneelleni.

![install apache](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/1f1f1821-7886-416f-809a-91363d0330a8)

Asennuksen jälkeen varmistin, että asennus onnistui. Ajoin "sudo systemctl status apache2" komennon ja totesin, että asennus onnistui koska apache oli käynnissä.

![apache_running](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/a15ce6e2-c884-45ff-9530-ac2109e7f983)

Tässä on polku, josta löytyy index.html tiedosto. Sen kun ajaa niin pääsee apachen kotisivuille.

![index polku](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/0b8c134d-839b-42cd-b831-307895e005b8)

Komento siis on "firefox index.html" ja tämä avaa firefox selaimen ja sieltä välilehden, johon aukeaa apachen kotisivu.

![firefox komento](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/eb36563b-4be7-420d-a6ef-4b3f4614cea4)

![apache home page](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/37fd9726-beda-4b7b-9cc6-300c4ceaa954)

Seuraavaksi ajattelin kuinka voisin saada selaimen avaamaan oman sivun. Ajoin "sudo gedit index2.html" komennon ja minulle aukesi editori.

![index2 komento](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/96b5bb0e-8936-48f5-942a-171b2024359d)

Editorissa laitoin sinne seuraavat tiedot ja tallensin sen. 

![oikea index2](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/baa3a683-a9f3-4eba-acea-268aa17749fe)

Seuraavaksi ajoin jo tutuksi tulleen komennon "firefox index2.html".

![firefox index2 komento](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/2b0d5074-61ac-412f-aee1-4cb2289ef8fe)

Selaimeen aukesi haluamani sivu, joten onnistuin.

![firefox index2](https://github.com/JoonasKal/Palvelinten-hallinta/assets/104196551/25fd7d01-4f0b-48b5-8e3f-ebb9d7bcd06b)



