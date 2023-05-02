a) Tehtävän tavoite oli asentaa salt windowsille. Menin saltstack sivustolle ja sieltä valitsin tiedoston, jonka latasin windowsille. Latauksen jälkeen asensin ohjelman.

![lataus](https://user-images.githubusercontent.com/104196551/235686561-bd0c875b-e0f4-4742-859e-7c75b4d84f3f.png)

Avasin Powershellin administrator oikeuksilla ja näin, että salt oli siellä kuvissa näkyvien komentojen avulla.

![salt](https://user-images.githubusercontent.com/104196551/235686623-10617554-a50d-428a-b10c-4fe6af163ed5.png)


![ls salt](https://user-images.githubusercontent.com/104196551/235686647-7bc69e2e-26b8-4387-b886-dfbb958ae418.png)

b) Kokeilin salt-call –local pingaus komentoa seuraavalla komennolla: ./salt-call –local test.ping ja sain vastaukseski true.

![localping](https://user-images.githubusercontent.com/104196551/235686772-528d00a0-7676-4c0b-9fa1-c9a5be5ba661.png)

d) Asensin windowsille ohjelman saltin avulla. Päätin asentaa ensiksi chocon. Kuvassa näkyvän komennon löysin netistä ja päätin kokeilla toimiiko se ja sehän toimi. 

![asennus choco](https://user-images.githubusercontent.com/104196551/235686863-8b532a4e-e679-4930-b4f4-d6d2ee105801.png)

Katsoin choco -v komennolla sen version.

![choco versio](https://user-images.githubusercontent.com/104196551/235686905-de80dc8e-4a85-4908-9638-05d9f2c35c48.png)

Päätin vielä asentaa notepad++ chocon avulla. Ajoin choco install notepadplusplus.install -y komennon ja se toimi.

![notepad asennus](https://user-images.githubusercontent.com/104196551/235686961-d19248f8-7446-4482-8f21-466dd327a140.png)


![notepad varmistus](https://user-images.githubusercontent.com/104196551/235686982-78a5d8b6-14a5-4603-9918-d7960ac61e5d.png)
