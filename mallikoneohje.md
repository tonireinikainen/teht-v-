# Ohje mallikoneen tekoon
    
### Audit-tilaan pääsy  
  
- Audit-tilaan pääsee Windowsin asennuksessa painamalla ***CTRL+Shift+F3***  
- Ennen näppäinten painamista kannattaa edettä asennuksessa vaiheeseen, jossa  
näppäimistön kielet, kiintolevyn jakamiset yms. on tehty. Ei kuitenkaan valita muita kieliasetuksia.  
  
### Audit-tilassa tehtävät säädöt  
  
- Ensimmäisenä kannattaa laittaa pakolliset Windows-päivitykset pyörimään, sillä niissä kestää aina oma aikansa  
- Seuraavaksi voi halutessaan asentaa koneelle BGinfon, jolla koneen nimen IP:n toimialueen yms. saa näkyviin  
- BGinfolla saa myös halutessaan saman taustakuvan kaikille koneille, jotka mallikoneesta luodaan
- Koneelle voi tässä vaiheessa myös asentaa tarvittavat ohjelmat, joita voisi olla esimerkiksi:  
  <ul>
      <li>Google Chrome</li>  
      <li>Kuvankäsittelyohjelma</li>  
      <li>Virustorjunta</li>  
  </ul>  
- Näistä ohjelmista voi sitten halutessaan luoda pikakuvakkeet julkiselle työpöydälle,  
jotta ne ovat joka kerta mallikonetta käytettäessä kaikilla käyttäjillä työpöydällä valmiina
  
### SysPrep  
- SysPrepiin pääsee polulla **C:\Windows\System32\Sysprep**  
- Graafisesti tuolta löytyy Sysprep.exe, jonka kautta preppauksen pääsee tekemään  
  
### Vastaustiedoston luominen  
- Vastaustiedosto luodaan Windows System Image Managerilla, johon avataan Windows-katalogi.  
- Katalogista sitten poimitaan oikeat palikat, jotta asennus on automattinen. Näitä palikoita ovat esimerkiksi:  
  <ul>
      <li>Kieli- ja aikavyöhykeasetukset</li>  
      <li>Tietokoneen omistajatiedot</li>  
      <li>Admin käyttäjätunnuksen ja salasana</li>  
  </ul>  
- Kun kaikki tarvittavat palikat on vastaustiedostoon laitettu, se tallennettaan Sysprep kansioon  
- Tämän jälkeen avataan sysprep.exe ja valitaan sieltä järjestelmän puhdistustoiminnosta: siirry tervetuloa ohjelmaan  
sulkemisvaihtoehdoista valitaan: sammuta  
- Tämä jälkeen kone on valmis exportiin ja kloonattavaksi  
  
  
# THE END
