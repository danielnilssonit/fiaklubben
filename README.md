# Fiaklubben

Fia med knuff i 3D, för surfplatta, mobil och dator. Ett träbräde på köksbordet, pjäser som hoppar ruta för ruta
och en tärning som rullar i en filtbricka. Gjort för att vara lugnt och tydligt, så att mormor kan spela med släkten.

**Spela:** https://danielnilssonit.github.io/fiaklubben/

- **Mot datorn** (lätt, medel eller svår), **flera vid samma skärm** eller **online** med två till fyra spelare.
- Klassiska regler: ut på etta eller sexa, sexan tar ut två pjäser och ger ett slag till, tre försök när alla är hemma,
  knuff, och studs vid målet. Husregler går att välja (bara sexa, murar, exakt slag i mål med mera).
- *Lugnt och tydligt*: lugnare tempo, större text, en röst som säger tärningens tal och vems tur det är, man ser vart
  pjäsen går innan den flyttas och kan ångra. Tipsknapp.
- **Online:** tryck på *Spela online*, skapa ett bord och dela länken eller QR-koden. Tomma platser fylls med datorer.
- På iPhone och iPad: *Dela → Lägg till på hemskärmen*, så startar spelet som en app.

Spelarna hittar varandra via öppna MQTT-servrar (inga konton, ingen egen server). Den som skapar bordet slår
tärningen och håller reda på spelet, och allt värden skickar är signerat. Namnen man väljer syns för andra i lobbyn.

3D-modellerna är gjorda i Blender, rösten och musiken med ElevenLabs, och spelet använder Three.js. Den här mappen
byggs automatiskt (tools/build-pages.mjs i projektet).
