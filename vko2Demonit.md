Ensimmäiseksi otin yhteyden masteriin "vagrant ssh tmaster" -komennolla. Seuraavaksi ajoin kuvassa näkyvät komennot

![salt-master asennus](https://user-images.githubusercontent.com/104196551/231207759-4a7f40e1-f62b-41d0-a78b-1ecf096ad15c.png)

Tämän jälkeen otin yhteyden orjaan ja asensin salt-minionin.

![asennus slave](https://user-images.githubusercontent.com/104196551/231209423-31ba5a7a-70c4-4a68-be6c-8d560674736b.png)

Seuraavaksi annoin sille nimen (id).

![slave id](https://user-images.githubusercontent.com/104196551/231210253-6f85a856-9f67-4f0f-a101-18e3a3e638b9.png)

![slave edit](https://user-images.githubusercontent.com/104196551/231210321-764abe26-e536-4c7f-bda8-8685f544b2b7.png)

Seuraavaksi käynnistin orjan uudelleen, jotta muutokset tallentuvat.

![restart slave](https://user-images.githubusercontent.com/104196551/231210940-11f97533-b180-4769-bc21-17525a95cc20.png)

Hyväksyin avaimen masterilla.

![avaimen hyväksyminen ](https://user-images.githubusercontent.com/104196551/231211076-ab49505f-f7ae-4ed3-a3eb-bf7ff30e227e.png)

Testasin, että se toimii.

![testi 'whoami'](https://user-images.githubusercontent.com/104196551/231211037-d0f008ee-713a-44c9-af3b-dcc241d5590c.png)

Tein ohjeiden mukaan sshd.sls ja sshd_config tiedostot, mutta kun ajoin komentoa " sudo salt '*' state apply sshd" sain tällaisen errorin.

![error](https://user-images.githubusercontent.com/104196551/231211140-b140ec48-4f30-4dc2-885d-ea7032c43e45.png)
