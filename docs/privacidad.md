# Política de privacidad de PinDesk

[← Volver al inicio](../README.md) · [English](../en/privacy.md)

Esta política explica qué datos trata la aplicación **PinDesk** (para Windows, Android, Mac e iPad,
incluida **PinDesk Plantillas**), para qué y qué puedes hacer con ellos. Vale para todas sus
ediciones, también la de Google Play.

Fecha de entrada en vigor: 7 de noviembre de 2026. Última actualización: 22 de noviembre de 2026.

> **En pocas palabras**
>
> - Lo que creas en PinDesk se guarda **en tu aparato**.
> - Para usar PinDesk **entras con Google o con tu correo** (te mandamos un código de 6 cifras).
>   Guardamos tu correo y, si entras con Google, tu nombre y tu foto: solo para tu cuenta, tu plan y
>   tu cupo.
> - Puedes **borrar tu cuenta** cuando quieras: en la app (**Cuenta › Borrar mi cuenta**) o en
>   **https://api.mairumax.me/borrar-cuenta**.
> - **Los pagos los procesa Google Play** (o el proveedor de pago que elijas fuera de Play). No vemos
>   ni guardamos los datos de tu tarjeta.
> - Lo que pides a la **IA** pasa por nuestro servidor hasta el proveedor de IA, o va directo al
>   proveedor si pones tu propia clave. **No lo guardamos.**
> - **No hay publicidad, ni analítica, ni informes de fallos, ni rastreo.** No vendemos datos.
> - La sincronización por **Wi‑Fi** va cifrada directamente entre tus aparatos, sin pasar por
>   internet.
> - Pasar la voz a texto y leer el texto de las imágenes se hacen **en tu aparato**, salvo las
>   funciones de voz en la nube que se explican en la sección 5.

Contenido: [1 Responsable](#1-quién-es-el-responsable) · [2 Tu cuenta](#2-tu-cuenta) ·
[3 En tu aparato](#3-datos-que-se-quedan-en-tu-aparato) ·
[4 Lo que sale](#4-datos-que-salen-de-tu-aparato) ·
[5 Voz](#5-voz-a-texto-y-lectura-en-voz-alta) · [6 Pagos](#6-pagos) ·
[7 Sincronización y copias](#7-sincronización-papelera-y-copias-de-seguridad) ·
[8 Lo que no hacemos](#8-lo-que-no-hacemos) ·
[9 Conservación y borrado](#9-conservación-y-borrado) ·
[10 Permisos](#10-permisos-y-servicios-en-primer-plano) · [11 Seguridad](#11-seguridad) ·
[12 Público y menores](#12-público-al-que-se-dirige-y-menores) · [13 Derechos](#13-tus-derechos) ·
[14 Transferencias](#14-transferencias-internacionales) · [15 Cambios](#15-cambios-en-esta-política) ·
[16 Contacto](#16-contacto)

## 1. Quién es el responsable

PinDesk la desarrolla **Max Anthony Mamani Maquera**, desarrollador independiente con domicilio en
Perú (en adelante, «nosotros»). Es el responsable de los datos que guarda el servidor de PinDesk
(`api.mairumax.me`), que se describen en las secciones 2, 4, 5 y 6. Para cualquier asunto de
privacidad, escribe a **max.antony.8.5.1@gmail.com**.

## 2. Tu cuenta

Para usar PinDesk hay que **entrar con una cuenta**. Puedes hacerlo de dos maneras:

- **Con Google**: eliges una de las cuentas de Google de tu aparato. Google nos confirma tu
  **correo**, tu **nombre** y tu **foto de perfil**, y un identificador de tu cuenta de Google, que
  guardamos solo en forma de huella (un resumen que no se puede revertir).
- **Con tu correo**: escribes tu correo y te mandamos un **código de 6 cifras** que vale 10 minutos
  y una sola vez. Del código solo guardamos una huella cifrada mientras vale, y cuántas veces se ha
  pedido y fallado (para frenar abusos). Con esta vía no guardamos nombre ni foto.

De tu cuenta guardamos en nuestro servidor: el correo, el nombre y la foto (si entraste con Google),
cómo entras (Google, correo o los dos), cuándo la creaste y cuándo la usaste por última vez, tu plan
(Gratis, la prueba de Pro o Pro) y hasta cuándo, los ajustes de tu cuenta que hagamos a mano (por
ejemplo, Pro regalado o un límite de uso) y lo que gastas cada día del **cupo** de las funciones
con IA (solo cuántas veces, nunca qué preguntaste).

Los usamos para:

- saber qué **plan** tienes y unir a tu cuenta lo que compres, en todos tus aparatos;
- darte el **asistente con IA sin poner ninguna clave**, con su cupo diario;
- **contestarte** si nos escribes por tu cuenta o un pago.

La app consulta nuestro servidor de vez en cuando para comprobar tu cuenta y tu licencia (que va
firmada, para que nadie la falsifique). En esa consulta no va nada de lo que creas. Tu sesión se
guarda en tu aparato, fuera de la copia de seguridad.

**Entrar con Google no nos da acceso a tu Drive, tu Calendar ni tu correo.** En Windows, eso solo
ocurre si conectas tú esos servicios para el asistente (sección 4), y se pide aparte.

Base legal: la ejecución del contrato que aceptas al usar PinDesk (los [Términos](terminos.md)).

## 3. Datos que se quedan en tu aparato

PinDesk guarda en su carpeta de datos (en Windows, `%APPDATA%\PinDesk`, o junto al programa en la
versión portátil; en Android, Mac e iPad, en el espacio privado de la app) lo que tú creas o traes:

- Chats, mensajes, notas, tareas, horarios, recordatorios, lecciones, plantillas, planos y
  documentos.
- Capturas de pantalla, pines, dibujos, fotos, vídeos, notas de voz y grabaciones de clases o
  reuniones.
- Transcripciones, los temas y lo apuntado de una reunión, y sus resúmenes ya hechos.
- Las palabras que le enseñas al dictado y tus ajustes.
- La **papelera** (lo que borras se guarda en ella 30 días) y las **copias de un proyecto** que la
  app hace sola antes de recibir o sincronizar algo encima, para poder volver atrás.
- Tu **sesión** y las **claves de API** que pegues (por ejemplo, las de Anthropic, DeepSeek,
  Soniox, TypeSafe o Brave Search): las claves se guardan **cifradas** con las protecciones del
  sistema (en Android, con una clave del almacén de claves del teléfono; en Windows, con tu usuario
  de Windows), nunca en el archivo de ajustes y nunca en la copia de seguridad.
- Los reportes de respuestas de la IA que hagas (sección 4).

Y estas cosas se hacen **en tu aparato, sin enviar nada**:

- El reconocimiento de texto en imágenes (OCR) y la lectura de PDF, Word, Excel y planos.
- Pasar a texto las grabaciones con los modelos que se ejecutan en el aparato (sección 5).
- **Tu ubicación**: en Android, la posición se usa solo cuando tocas «Mi posición» sobre un plano
  georreferenciado, para ponerte en el plano. No se guarda en ningún servidor y no se envía a nadie.
  Si tocas «Ver en el mapa», se abre OpenStreetMap con esas coordenadas en tu navegador.
- **Los widgets** de Android (Hoy, tareas, listas, galería, archivos recientes, acciones rápidas y
  clase) leen tus datos del aparato y los enseñan en la pantalla de inicio. No envían nada, pero
  cualquiera que vea tu pantalla verá lo que muestran: quítalos si no quieres que se vean.
- **Enviar a Anki**: escribe las tarjetas en AnkiDroid, dentro de tu teléfono.

Nosotros no tenemos acceso a estos datos mientras no salgan de tu aparato por una de las vías de las
secciones 4, 5 y 7.

## 4. Datos que salen de tu aparato

Además de lo de las secciones 2, 5, 6 y 7, algo sale de tu aparato **solo cuando usas una función
que lo necesita**. Todo viaja por conexión cifrada (HTTPS/TLS), y cada servicio de terceros trata
los datos según su propia política de privacidad. En Android, **Ajustes › Privacidad y datos**
resume esta lista; en Windows, **Ajustes → General → Privacidad y datos** la repite con un botón a
donde se enciende o se apaga cada función. Según tu plan, algunas funciones son de **Pro**.

| Función | Qué se envía | A quién |
|---|---|---|
| **Asistente con IA**, **Plantillas con IA**, **la llamada con IA** y **los documentos** (Excel, Word, PowerPoint, PDF) que hace el asistente | Lo que le escribes o le dices (ya pasado a texto), lo reciente de esa conversación y lo que adjuntes (una foto, una captura, un documento). | Sin clave propia: **nuestro servidor**, que lo reenvía a **Anthropic** (Claude) y cuenta tu cupo. Con tu propia clave: directo a **Anthropic** o **DeepSeek**, sin pasar por nosotros. |
| **Resúmenes y preguntas sobre una clase o reunión grabada** | El texto de la transcripción y tu pregunta (nunca el audio). | Nuestro servidor, que lo reenvía a Anthropic. |
| **Jev** (urgencia de tareas y temas de una reunión) | Fragmentos de texto (frases ya pasadas a texto en tu aparato, renglones de una nota, tareas) y, en algunas funciones, una imagen, para obtener una clasificación. **Nunca el audio.** | **TypeSafe**, solo con tu clave de TypeSafe y esa función encendida. |
| **Búsqueda web del asistente** | Los términos que busca para responderte y la dirección de las páginas que lee. Sin cookies, sin tu clave de IA y sin datos de tu cuenta. | **DuckDuckGo**, o **Brave Search** si pones tu clave de Brave; y la web que se lee. Se apaga en los ajustes del asistente. |
| **Galería de la comunidad** | Lo que decides publicar (una miniapp, una figura, una plantilla, un lienzo, un plano…), con su título, su descripción y tu nombre como autor; y tus «me gusta». | Nuestro servidor. Lo que publicas lo pueden ver y descargar los demás usuarios; tu correo no se enseña nunca. |
| **Figuras y bibliotecas del servidor** | Solo la petición de descarga. Nada tuyo. | Nuestro servidor. |
| **Conexiones de Google** (Windows) | Los archivos de Drive que eliges y los eventos del calendario que pides. | Google, solo si conectas esos servicios. Se desconectan desde Ajustes → Asistente. |
| **Compartir por enlace** | El archivo que eliges compartir. | Un servicio público de archivos temporales (litterbox.catbox.moe o temp.sh). Cualquiera con el enlace puede abrirlo hasta que caduque (de horas a días). No lo uses para algo privado. |
| **Descarga de modelos, diccionarios y herramientas** | Solo la petición de descarga (como en cualquier descarga, el servidor ve tu dirección IP). Nada tuyo. | Los sitios donde se publican: alphacephei.com (Vosk), Hugging Face y GitHub (Whisper, Qwen3-ASR, el detector de voz, el diccionario), y cdn.jsdelivr.net (Python para el asistente, al usarlo la primera vez). |
| **Actualizaciones** (solo las ediciones de fuera de Google Play) | Solo la consulta de cuál es la última versión. | Nuestro servidor y GitHub. La versión de Google Play se actualiza solo por Google Play. |
| **Enlaces y páginas que abres** | Lo gestiona tu navegador o el programa que elijas. Una página HTML que abras en PinDesk puede cargar imágenes o código de internet, como en un navegador. | La web o el programa de destino. |

**Sobre las peticiones de IA.** Cuando pasan por nuestro servidor, solo las reenviamos al proveedor
y te devolvemos la respuesta: **no guardamos su contenido** ni lo usamos para nada más. Del uso solo
apuntamos cuánto gastas de tu cupo cada día. Los documentos que hace el asistente se guardan en la
memoria del servidor solo hasta que tu aparato los recoge, y se borran de Anthropic en cuanto se
bajan. El proveedor de IA trata lo que recibe según sus propias condiciones: revísalas antes de
enviarle información sensible.

**Contenido generado por IA.** Las respuestas las genera un modelo de terceros y pueden contener
errores. Puedes informar de una respuesta inadecuada con **Reportar respuesta…** (menú del mensaje
› Más, o la bandera de la respuesta; en Android también en Ajustes › Privacidad y datos): eliges el
motivo, se guarda en tu aparato y se abre tu programa de correo con el reporte escrito, para que nos
lo mandes si quieres. Solo nos llega lo que tú decidas enviar.

## 5. Voz a texto y lectura en voz alta

PinDesk puede pasar tu voz a texto de varias maneras. **La mayoría funcionan en tu aparato, sin
red**; las que usan la nube se dicen aquí, y ninguna guarda tu audio en nuestro servidor.

| Motor | Dónde se hace | Qué sale y a quién |
|---|---|---|
| **Vosk**, **Whisper** y **Qwen3-ASR** (modelos que bajas una vez) | En tu aparato. | Nada (solo la descarga del modelo, sección 4). |
| **El reconocedor de voz del teléfono** (el de Google u otro que traiga tu teléfono) | Lo hace el servicio de voz del sistema. | Según tu teléfono y su configuración, ese servicio puede funcionar sin red o enviar el audio a su proveedor (por ejemplo, Google), que lo trata según sus condiciones. |
| **Voz en la nube de la llamada con IA** (Whisper en Groq) | En la nube, frase a frase. | El audio de cada frase que dices en la llamada va a **nuestro servidor**, que lo pasa a texto con **Groq** y te devuelve el texto. **No guardamos el audio ni el texto.** Mientras tanto, Vosk también lo pasa a texto en tu aparato, por si falla la red. |
| **Voz en vivo de alta precisión** (Soniox) | En la nube, mientras hablas. | Con **tu propia clave de Soniox** (Ajustes › Agente), el audio va **directo de tu aparato a Soniox**, sin pasar por nuestro servidor; con él van las palabras que le enseñaste al dictado y un poco de contexto (por ejemplo, nombres de tus archivos) para que entienda mejor. Si un día lo damos con la cuenta, nuestro servidor solo te da una clave temporal de un solo uso y el audio sigue yendo directo a Soniox. Se puede apagar en Ajustes › Agente. |

**Lectura en voz alta.** El lector usa la **voz del teléfono** (sin red). En las ediciones de fuera
de Google Play, y en Windows, puedes elegir además una de las **voces en línea de Microsoft**:
entonces el texto que se lee va a Microsoft para convertirlo en audio, y el audio que vuelve se
guarda en tu aparato para no pedirlo otra vez. La versión de Google Play no tiene las voces de
Microsoft.

## 6. Pagos

**En la versión de Google Play**, PinDesk Pro (mensual, anual o de por vida) se compra con **Google
Play Billing**: el pago lo hace Google y tus datos de pago **los trata Google, no nosotros**. Para
darte Pro, la app nos manda el **comprobante de la compra** (el *token* de compra y el producto) y
nuestro servidor lo **comprueba con Google** (la API de Google Play para desarrolladores) antes de
activarlo; Google nos avisa también de las renovaciones, cancelaciones y devoluciones. En la compra
va un identificador de tu cuenta de PinDesk **cifrado** (sin datos personales), para saber de quién
es. Las suscripciones se cancelan en Google Play.

**Fuera de Google Play**, el pago lo procesa un **proveedor de pago** (por ejemplo, Mercado Pago o
Lemon Squeezy, según el medio que elijas). Tus datos de pago (número de tarjeta, cuenta del medio de
pago) **los recibe y los trata ese proveedor, no nosotros**. **No guardamos los datos de tu
tarjeta.**

De cada compra guardamos solo lo necesario para activar tu licencia, darte soporte y cumplir
nuestras obligaciones legales y contables: la cuenta a la que pertenece y su correo, el proveedor,
el plan comprado, el importe y la moneda cuando el proveedor nos los da, las fechas, el estado
(activa, renovada, cancelada, caducada o reembolsada) y el identificador de la operación.

Base legal: la ejecución del contrato de compra y el cumplimiento de obligaciones legales.

## 7. Sincronización, papelera y copias de seguridad

### Por Wi‑Fi (todos los planes)

Tus aparatos se encuentran por la red local y se emparejan con un código o un QR. Todo lo que viaja
va **cifrado** con una clave que solo conocen tus aparatos, directamente de uno a otro, **sin
servidores intermedios en internet**. Igual va el móvil cuando lo usas como cámara del PC. Si
compartes un chat con otra persona, esa persona recibe una copia en su aparato.

Lo que borras en un aparato se borra también en los demás al sincronizar, y queda **30 días en la
papelera** de cada uno, con el nombre del aparato donde se borró, por si quieres recuperarlo.

### Por la nube (chats compartidos)

Un chat compartido puede ir, además, **por una nube**: un servidor cuya dirección y llave pones tú
en **Sincronizar › Nube** (por ejemplo, el de tu equipo de trabajo). Entonces los mensajes, archivos
y cambios de ese chat se suben a **ese servidor**, cifrados en el camino, y de ahí los bajan las
demás personas del chat. Tus chats personales siguen solo por la red local. Quien gestiona ese
servidor es responsable de lo que guarda; si lo gestionamos nosotros para ti, usamos esos datos
**solo para sincronizarlos**: no los miramos, no los analizamos y no los usamos para nada más, salvo
que nos pidas ayuda con un problema o una ley o autoridad competente nos obligue.

### Copias de seguridad

- **La copia de seguridad de Android** (la de tu cuenta de Google, si la tienes activada) puede
  incluir tus datos de PinDesk, como los de cualquier app. **No incluye** tus claves de API, tu
  sesión, el código de tu grupo de sincronización ni la llave de tus chats compartidos: en un
  teléfono nuevo vuelves a entrar y a emparejar. El traspaso directo de un teléfono a otro (por
  cable o Wi‑Fi) sí lleva tus chats compartidos, pero no la identidad del aparato.
- **Las copias de un proyecto** que hace la app (sección 3) se quedan en el aparato y no viajan.

Base legal: la ejecución del contrato (el servicio que pides al sincronizar).

## 8. Lo que no hacemos

- No mostramos publicidad ni usamos identificadores publicitarios.
- No usamos analítica, informes de fallos remotos ni rastreadores. Los registros de la app se quedan
  en tu aparato (en la llamada con IA puedes copiar un informe técnico para mandárnoslo, si
  quieres).
- No vendemos, alquilamos ni cedemos datos personales.
- No guardamos lo que preguntas a la IA ni el audio de tu voz.
- No usamos tus datos para entrenar modelos de IA. (Los proveedores de IA a los que envías datos
  tienen sus propias condiciones; revísalas.)

## 9. Conservación y borrado

### Borrar tu cuenta

Puedes borrar tu cuenta cuando quieras, de dos maneras:

- **En la app**: **Cuenta › Borrar mi cuenta**, y escribes la palabra que te pide para confirmarlo.
- **Sin la app** (por ejemplo, si ya la desinstalaste): en
  **[https://api.mairumax.me/borrar-cuenta](https://api.mairumax.me/borrar-cuenta)** escribes el
  correo de tu cuenta y te mandamos un enlace (vale una hora) para confirmarlo con un botón.

Al borrarla se borran **para siempre** de nuestro servidor: tu cuenta (correo, nombre y foto), tu
licencia y tu Pro, tus cupos, tu código de correo pendiente y lo que publicaste en la galería de la
comunidad. **Tus compras se desvinculan**: se quita de ellas tu cuenta y tu correo, y se conserva
solo lo que exige la ley contable (sin datos personales). La suscripción sigue en Google Play (o
donde pagaste) y hay que cancelarla allí. Queda solo un apunte sin datos personales de que se borró
una cuenta (cuándo, por dónde y cuántas compras se desvincularon). Lo que tienes en tu aparato no se
toca: solo se cierra la sesión.

La cuenta que usan los revisores de Google Play para probar la app es la única que no se puede
borrar.

### Plazos

- **En tu aparato**, tus datos se conservan hasta que los borres. En Android, **Ajustes ›
  Privacidad y datos › Borrar todos mis datos** borra todo lo de la app en el teléfono (también
  desinstalarla). En Windows, **Ajustes → General → Tus datos, en tu disco** abre la carpeta de
  datos: cópiala para llevártelos, o cierra PinDesk y bórrala para quitarlo todo. Desinstalar
  PinDesk en Windows puede dejar esa carpeta (para no perder tus cosas por error); bórrala a mano si
  quieres. Cómo hacerlo: [Desinstalar](instalar.md#desinstalar).
- **La papelera** guarda lo borrado 30 días y después se vacía sola.
- **Tu cuenta** se conserva mientras no la borres.
- **El código de entrar con correo** caduca a los 10 minutos y sirve una sola vez.
- **Los datos de pago** que guardamos (sección 6) se conservan el tiempo que exige la ley tributaria
  y contable, aunque borres tu cuenta (desvinculados de ella).
- **Las copias de seguridad de nuestro servidor** se sobrescriben en un plazo de hasta 30 días.
- **Lo que enviaste a un tercero** (secciones 4 y 5) se rige por ese servicio. Los enlaces
  temporales caducan solos.
- **Las copias en tus otros aparatos**, o en los de las personas con quienes compartiste un chat, se
  borran en esos aparatos.

## 10. Permisos y servicios en primer plano

PinDesk pide cada permiso **cuando usas la función que lo necesita**, no al instalarla.

- **Micrófono**: notas de voz, dictado, la llamada con IA y grabar clases o reuniones; solo
  mientras lo usas.
- **Cámara**: fotos, vídeos, leer un QR, el croquis 3D, la reunión presencial y usar el móvil como
  cámara del PC; solo cuando la eliges.
- **Grabar o capturar la pantalla**: solo cuando tú lo inicias (una captura, un clip o la grabación
  de la pantalla). Android te pide permiso cada vez y enseña que se está grabando.
- **Ubicación** (Android): solo «Mi posición» sobre un plano, con la app abierta. Nunca en segundo
  plano y nunca sale del teléfono.
- **Mostrar sobre otras apps** (Android): los pines flotantes y la bolita.
- **Red y Wi‑Fi**: entrar, comprobar tu licencia, las funciones de las secciones 4 y 5 y la
  sincronización (encontrar tus aparatos en la red local).
- **Notificaciones, alarmas exactas y arrancar con el sistema**: los avisos de tareas, clases y
  evaluaciones y los recordatorios a su hora, también después de reiniciar el aparato.
- **AnkiDroid**: solo si usas «Enviar a Anki».

**Servicios en primer plano** (Android). Cuando algo tiene que seguir con la app fuera de la
pantalla, Android lo hace con un servicio en primer plano y enseña **una notificación todo el
tiempo** que dura, desde la que se puede parar: grabar una clase o una reunión (micrófono, y cámara
en la reunión presencial), grabar la pantalla, la llamada con IA, escuchar un documento en voz alta,
los pines flotantes, pasar a texto una grabación o bajar un modelo, y sincronizar o enviar tus
archivos a tus aparatos. Ninguno de estos servicios envía nada a internet por su cuenta: hacen lo
que tú empezaste.

PinDesk no lee tus contactos, tu calendario del teléfono, tus mensajes ni tus correos.

## 11. Seguridad

Tus claves se guardan cifradas en tu aparato. Las conexiones a internet usan HTTPS, la
sincronización por Wi‑Fi va cifrada entre tus aparatos y tu licencia va firmada. En el servidor, el
código de entrar con correo se guarda solo como huella, hay límites de intentos y el acceso está
limitado a lo imprescindible. Ningún sistema es infalible: protege tu aparato y tu cuenta de Google
o de correo con contraseña y, si puedes, con verificación en dos pasos. Si ocurriera un incidente de
seguridad que afecte a tus datos, te lo comunicaremos y avisaremos a la autoridad cuando la ley lo
exija.

## 12. Público al que se dirige y menores

PinDesk está pensada para **personas adultas (18 años o más)**: estudiantes universitarios y
profesionales. No está dirigida a niños y no recoge conscientemente datos de menores. Las funciones
de IA usan servicios de terceros que exigen ser mayor de edad (por ejemplo, Anthropic exige 18
años). Si eres menor de edad, no uses PinDesk sin el permiso y la supervisión de tus padres o
tutores. Si crees que un menor nos ha dado datos, escríbenos y borraremos su cuenta.

## 13. Tus derechos

Según la ley que te aplique (por ejemplo, la **Ley 29733 de Protección de Datos Personales** del
Perú y su reglamento, el **RGPD** en la Unión Europea o la LOPDGDD en España), tienes derecho a
**acceder** a tus datos, **rectificarlos**, **cancelarlos o suprimirlos**, **oponerte** a su
tratamiento y, cuando corresponda, a la **portabilidad**. Los datos que están en tu aparato los
controlas tú directamente. Tu cuenta la puedes borrar tú mismo (sección 9). Para cualquier otra
cosa sobre tu cuenta o tus pagos, escríbenos a **max.antony.8.5.1@gmail.com** desde el correo de
tu cuenta; te contestaremos en los plazos que fija la ley.

También puedes reclamar ante tu autoridad de protección de datos: en Perú, la **Autoridad Nacional
de Protección de Datos Personales** (Ministerio de Justicia y Derechos Humanos); en España, la AEPD.

## 14. Transferencias internacionales

Nuestro servidor, Google, los proveedores de pago y los de IA y voz (Anthropic, Groq, Soniox y, si
eliges DeepSeek, DeepSeek) pueden estar fuera de tu país (por ejemplo, en Estados Unidos, la Unión
Europea o, con DeepSeek, en China). Al usar esas funciones, tus datos pueden tratarse allí.
Elegimos proveedores que ofrecen garantías adecuadas de protección.

## 15. Cambios en esta política

Si cambiamos esta política, publicaremos la nueva versión en esta misma dirección con su fecha. Si
el cambio es importante, también lo avisaremos dentro de la aplicación antes de que se aplique.

## 16. Contacto

**Max Anthony Mamani Maquera** · Correo: **max.antony.8.5.1@gmail.com**

Esta política también se puede leer en **https://api.mairumax.me/privacidad** (en inglés,
**https://api.mairumax.me/privacy**).
