# TOLE2 Li
Editor de Excel/CSV, Word (.docx) y texto + escáner a PDF. Offline y online, con autocorrector.
## APK sin instalar nada (desde el navegador)
1. GitHub: repo nuevo > "Upload files" > sube TODO este contenido.
2. Firebase (opcional, para la nube): console.firebase.google.com > nuevo proyecto > Authentication (activa Correo/contraseña) > Storage (crear) > pega las reglas de storage.rules > Configuración > app Web > copia la config en www/firebase-config.js (edítalo en GitHub).
3. codemagic.io > entra con GitHub > agrega el repo > "codemagic.yaml" > Start build > workflow "apk" > descarga el .apk.
4. Icono de la app: sube tu imagen cuadrada (1024x1024) como resources/icon.png y vuelve a compilar.
La portada, el logo y el fondo se cambian dentro de la app, en Ajustes.

## Escuchar (audiolibro)
Pestaña 🎧: abre EPUB, PDF, Word, Excel, CSV o texto y lo lee en voz alta, con velocidad, idioma, temporizador y marcador automático. Usa las voces de tu teléfono (sin internet si tienes voz en español instalada).

## Personalizar (Ajustes)
- Guardar sobrescribe el archivo en la pestaña Archivos; 'Guardar como' crea otro; 'Enviar' lo comparte o descarga.
- Fondos: agrega varias imágenes y toca una para cambiar (o activa el cambio automático al abrir).
- Fuentes propias: carga .ttf/.otf/.woff y úsalas en la interfaz, el editor o dentro de un Word.
- Logo de la app (cabecera) y logo de inicio (pantalla de inicio) se cargan en la app. Para el ICONO del celular: 'Exportar icono 1024', sube ese icon.png a GitHub en resources/icon.png y recompila.

## Escritura y vista
- Diccionario predictivo: sugiere palabras sobre el teclado y aprende las tuyas (solo se guardan en el teléfono). Se activa o desactiva en Ajustes.
- Cabecera: A− / A+ cambian el tamaño de la pantalla (toca el % para volver a 100%) y el botón ☀️/🌙 alterna tema claro y oscuro.

## Formatos
Abre y edita: Excel (xlsx, xlsm, xlsb, xls), OpenDocument (ods), CSV/TSV, Word (docx), HTML, texto y código. Convierte a texto editable: EPUB, PowerPoint (pptx), OpenDocument (odt, odp), RTF. PDF: visor de páginas, extraer texto para editar, escuchar y exportar cualquier documento a PDF. Imágenes: ver y convertir a PDF. Los .doc/.ppt antiguos hay que pasarlos antes a .docx/.pptx.

## Voces
Pestaña 🎧 > Voces: elige la voz del narrador entre las instaladas en el teléfono (♀/♂ estimado por el nombre), un estilo de personaje genérico (niño, anciano, villano, robot…) y opcionalmente otra voz para los diálogos (líneas con — o comillas). Para más voces: Ajustes de Android > Salida de texto a voz.
