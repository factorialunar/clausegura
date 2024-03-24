# Generador de contrasenyes

Aquesta pàgina web permet crear contrasenyes des del navegador. Pots consultar-la a https://clau.factoria.lu.

## Què fa aquesta pàgina web?

Crear una contrasenya de la longitud desitjada, amb els grups de caràcters que es vulgui, des del navegador web.

## Què no fa aquesta pàgina web?

Gestionar les contrasenyes. Un cop generades, és l'usuari qui les ha de desar de manera adient.

## En què es diferencia d'altres serveis similars?

Aquesta pàgina web no utilitza galetes (*cookies*) ni envia cap informació sobre l'usuari o les contrasenyes generades a cap servidor.

Les contrasenyes es generen en l'ordinador de l'usuari, a través del navegador.

## Són segures aquestes contrasenyes?

Es generen a través del mètode [generateKey](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/generateKey) de la interfície de programació [Crypto.subtle](https://developer.mozilla.org/en-US/docs/Web/API/Crypto/subtle) de Javascript, que és el mètode recomanat per a generar contrasenyes des del navegador.

Dit això, la seguretat depèn de molts factors, principalment de si l'usuari confia en l'ordinador on està usant aquesta pàgina web per generar contrasenyes. Considereu altres mètodes si necessiteu garantir la seguretat en extrem.

## Llicència

Del codi en aquest repositori: [GPLv3](LICENSE).
