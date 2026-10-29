# Rastreador de Huellas Formoseño

Juego de realidad aumentada del proyecto **DIA (Didáctica con IA) · Aprendé jugando**.

Un juego de cacería en realidad aumentada, al estilo Pokémon GO: el animal se esconde de verdad en tu casa, el patio o la plaza, y lo buscás caminando con la cámara. Seguís sus huellas con el radar, lo identificás por la huella y le sacás la foto de campo para sumarlo a tu **Fauna-dex Formoseña**. Vas ganando XP y subiendo de nivel de rastreador.

## Misiones

1. **El Gran Excavador de Formosa Seca** — tatú carreta
2. **El Sembrador Silencioso** — tapir o mboreví
3. **El Caminante de los Pastizales** — aguará guazú
4. **El Depredador Invisible** — yaguareté
5. **Modo Paleo-RA: Rescate en Villa Escolar** — detector de fósiles: gliptodonte, perezoso gigante, toxodonte y yaguareté fósil
6. **Exploración libre** — cualquier especie puede aparecer, una cacería tras otra

## Cómo se juega

1. Elegí la zona: casa (3 m), patio (7 m) o plaza (14 m).
2. **Escaneá el lugar:** apuntá a muebles, mesas, árboles y rincones. El animal se esconde detrás o debajo de esos objetos reales, y gracias al sensor de profundidad lo real lo tapa en la cámara. Podés marcar un escondite («Esconder acá») o un río o pileta («Hay agua acá»): el tapir se mete al agua y se zambulle.
3. Seguí las huellas con el radar: aparecen cuando pasás cerca.
4. Analizá las huellas (tamaño, dedos, garras). Sin identificarlo, solo ves su silueta.
5. Sacale la foto cuando el aro se ponga verde. Tenés 3 rollos; si fallás, se escapa y deja un rastro nuevo.

## Equipos

- **RA completa con oclusión** (el animal se esconde detrás de los objetos reales): Android con Chrome, ARCore y soporte de profundidad (ARCore Depth API). Sin profundidad igual detecta objetos y esconde al animal, pero no puede recortarlo detrás de ellos.
- **Modo cámara con giroscopio:** iPhone y otros equipos. Safari no da acceso a la geometría del lugar, así que el animal se esconde detrás de objetos virtuales.
- **Modo sin cámara:** computadora o proyector del aula.

La cámara solo funciona si la página se abre con https (por ejemplo, desde GitHub Pages).

Todo está en un solo archivo, `index.html`, con el motor 3D incluido: funciona sin conexión.

---

Proyecto DIA · ISFD y T «República Federal de Alemania», El Colorado, Formosa.
Copyleft: copialo, compartilo y mejoralo.
