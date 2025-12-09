# System Check – luonnos

Tämä on konsepti perusjärjestelmätarkistuksesta, jota voidaan käyttää käyttäjän laitteella tehtävän nopean vianmäärityksen apuna.

## Tarkistettavat asiat

1. **Verkon saatavuus**
   - testataan, saako laite yhteyden ulkoverkkoon
   - tarkistetaan DNS-resoluutio

2. **Levytila**
   - onko käyttöjärjestelmän levyllä riittävästi vapaata tilaa
   - onko käyttäjän profiilihakemisto täynnä

3. **Suorituskyky**
   - käynnissä olevien prosessien määrä
   - muistinkäyttö

4. **Päivitykset**
   - onko järjestelmään saatavilla kriittisiä päivityksiä
   - onko viimeisin uudelleenkäynnistys tehty äskettäin

## Tavoite

Antaa nopea yleiskuva laitteen tilasta ennen tarkempia toimenpiteitä.

(Varinaiset komentosarjat voidaan toteuttaa myöhemmin eri kielillä.)
