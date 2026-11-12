# archiblocks-redes-publicas

Estante público para los videos que Archiblocks publica en sus redes sociales.

Existe por una razón concreta: **Instagram no recibe el archivo, lo descarga.** Su API pide una
`video_url` que se pueda abrir sin sesión, y nuestra app de Meta usa Facebook Login legacy, al que
Meta no le habilita la carga directa. Así que el video tiene que estar en una URL pública mientras
Instagram lo baja.

Acá no hay código ni historia: cada video va como **archivo de release**, fechado. El registro de
qué se publicó, con qué texto y en qué red vive en el repo de coordinación, en
`DIRECCION/MARKETING/PUBLICADOR/`.

Todo lo que se sube acá es material que de todas formas queda público en las redes.
