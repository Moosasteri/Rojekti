# Ohjeet mallikoneen tekemiseen  
## Miten pääset asennuksen aikana Audit tilaan  
*Kun olet valinnut kielen ja muut kielivalinnat paina näppäinyhdistelmä ctrl+shift+f3  
*Päivitä windowsiin uusimmat päivitykset updaten kautta  

## Miten mukauttaisit ympäristöä ennen sysprep ohjelman ajamista?  

*Kun windows update on päivittänyt koneen, voi halutessaan asentaa BGinfo ohjelman jolla saa työpöydälle näkyviin tietoja koneesta.  

## Miten Sysprep ohjelmaa käytetään graafisen työkalun ja/tai komentokehotteen kautta?  

*Ohjeet Sysprep ohjelmankäynnistykseen komentokehotteen kautta. Komennolla %WINDIR%\system32\sysprep\sysprep.exe saat avattua suoritakomentoa käyttäen SysPrep ohjelman. Voit käyttää Suorita komennossa myös seuraavia komentoja /generalize, /shutdown, and /oobe. 

## Kuvaa vastausiedoston luomista yleisellä tasolla. Halutessasi voit kirjata mukaan myös asetukset esim. kuvaruutukaappauksin tai muulla tavalla.  

![image](https://user-images.githubusercontent.com/106652624/173004818-c1c8cfa8-b701-41a8-9c31-10de2d0b4a7f.png)  

## Miten vastaustiedostoa käyttö yhdessä sysprep ohjelman kanssa (vastaustiedoston sijainti valmisteltavassa työasemassa ja sysprep ohjelman parametrit)?  

* Vastaustiedoston sijaintina C:\Windows\system32\sysprep, Sysprepille pitää osoittaa tiedot suoritakomennolla: sysprep /generalize /oobe /unatttend:C:\path\to\unattend\filename.xml /shutdown




