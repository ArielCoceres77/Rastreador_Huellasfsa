# Rastreador de Huellas Formoseño

Juego de realidad aumentada del proyecto **DIA (Didáctica con IA) · Aprendé jugando**.

Recorré tu casa, el patio, la escuela o la plaza con la cámara del celular. El rastreador **reconoce los objetos reales** (sillones, sillas, mesas, camas, plantas, bancos, bicis, autos, heladeras…) y **detrás de cada uno se asoma un animal de Formosa**, recortado con la silueta del objeto. Si el objeto es chico, el animal es chico; si es grande, puede ser grande; detrás de un auto o un camión aparece megafauna del Pleistoceno. ¿Un árbol o una roca? Tocalo en la pantalla y lo revisa igual.

Reconocé al animal antes de que se acabe el tiempo:

- Acierto: **+100**, más bonus por rapidez y por racha.
- Error: **−50**. Si se acaba el tiempo: **−25**.
- Oír su sonido: −10. Pista: −20.

## Fauna

Mulita, tatú carreta, zorro de monte, gato onza, mono carayá, carpincho, corzuela parda, pecarí de collar, aguará guazú, puma, yaguareté, oso hormiguero, yacaré overo, jabirú, ñandú y tapir. Megafauna: gliptodonte, perezoso gigante y toxodonte.

Cada animal reconocido queda en la **Fauna-dex Formoseña** con su ficha.

## Modos

- **Con la cámara:** Android, iPhone o la compu con cámara. La página tiene que abrirse con https (GitHub Pages).
- **Monte virtual:** sin cámara, para probar o para el proyector del aula.

## Técnica

- Detector de objetos y recorte por toque con MediaPipe (carpeta `mp/`). Los modelos se descargan de Google la primera vez, así que hace falta internet; después quedan en la caché del navegador.
- Animales en 3D con three.js, incluido en `index.html`.

---

Proyecto DIA · ISFD y T «República Federal de Alemania», El Colorado, Formosa. Copyleft: copialo, compartilo y mejoralo.
