# Ensimmäinen tehtävä

Ensimmäiseksi asensin Virtualboxin Vagrantilla.

<img src="https://user-images.githubusercontent.com/104196551/229482751-3b7559ab-264c-4bbd-ade4-d9cfc33d880d.png" width="500" height="350" />

Seuraavaksi tein hakemiston nimeltä VagrantFile, jonne lisäsin vaaditut tiedot.

<img src="https://user-images.githubusercontent.com/104196551/229485591-a3a4334f-7eb7-4b15-b27b-3b3a1d7f02f2.png" width="500" height="250" />

Käynnistin koneet komennolla "Vagrant up". Tämän jälkeen otin yhteyden tmaster koneeseen komennolla "vagrant ssh tmaster".
Seuraavaksi käskin orjia näyttämään niiden Interfacen.

<img src="https://user-images.githubusercontent.com/104196551/229491442-1ab227a2-462c-4855-9429-c43e976bee5a.png" width="500" height="200" />

<img src="https://user-images.githubusercontent.com/104196551/229487902-8845114e-bb39-4228-9a3a-9742b590c03f.png" width="500" height="100" />

Seuraavaksi käskin orjien esittämään niistä tietoa.

<img src="https://user-images.githubusercontent.com/104196551/229488849-5c720dc4-3b0e-4b68-8a05-d59518b987f5.png" width="500" height="250" />

Seuraavaksi tein idempotent komentoja. Tein tiedosto ja se lisättiin. Kuten kuvassa näkyyn, ajoin komennon uudestaan ja "changed=1" tekstiä ei ilmaantunut,vaan jäljellä oli vain "Succeeded=1".

<img src="https://user-images.githubusercontent.com/104196551/229489624-e08649f7-35da-4d04-bd17-8896b2808c81.png" width="500" height="250" />

Seuraavaksi tein käyttäjän "joonaste01", muokkasin sen sijaintia ja lopuksi poistin sen.

<img src="https://user-images.githubusercontent.com/104196551/229492508-e9244308-8eb4-4b96-a71a-45afa8dbf84b.png" width="500" height="300" />

<img src="https://user-images.githubusercontent.com/104196551/229492571-5673af6c-6e49-4282-a423-750bfc8096ca.png" width="500" height="250" />

<img src="https://user-images.githubusercontent.com/104196551/229492608-d6159804-567b-44fd-a9be-45ade137d281.png" width="500" height="250" />
