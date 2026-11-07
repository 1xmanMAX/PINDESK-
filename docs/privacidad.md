# Política de privacidad de PinDesk

[← Volver al inicio](../README.md) · [English](../en/privacy.md)

Esta política explica qué datos trata la aplicación **PinDesk** (para Windows, Android, Mac e iPad,
incluida **PinDesk Plantillas**), para qué y qué puedes hacer con ellos.

Fecha de entrada en vigor: 7 de noviembre de 2026. Última actualización: 7 de noviembre de 2026.

> **En pocas palabras**
>
> - Lo que creas en PinDesk se guarda **en tu aparato**.
> - Para usar PinDesk inicias sesión con **Google**. De tu cuenta usamos tu **correo** y tu
>   **identificador de cuenta**, solo para tu plan, tus aparatos y la sincronización.
> - **Los pagos los procesan los proveedores de pago.** No vemos ni guardamos los datos de tu
>   tarjeta.
> - Con **Pro**, lo que eliges sincronizar por la nube se guarda en nuestros servidores, cifrado en
>   el camino.
> - Lo que pides a la **IA** se envía al proveedor de IA que tú eliges.
> - **No hay publicidad, ni analítica, ni informes de fallos, ni rastreo.** No vendemos datos.
> - La sincronización por **Wi‑Fi** va cifrada directamente entre tus aparatos, sin pasar por
>   internet.
> - Pasar la voz a texto y leer el texto de las imágenes se hacen **en tu aparato**.

Contenido: [1 Responsable](#1-quién-es-el-responsable) · [2 Tu cuenta](#2-tu-cuenta-de-google) ·
[3 En tu aparato](#3-datos-que-se-quedan-en-tu-aparato) ·
[4 Lo que sale](#4-datos-que-salen-de-tu-aparato) · [5 Pagos](#5-pagos) ·
[6 Sincronización](#6-sincronización) · [7 Lo que no hacemos](#7-lo-que-no-hacemos) ·
[8 Conservación y borrado](#8-conservación-y-borrado) · [9 Permisos](#9-permisos-y-para-qué-sirven) ·
[10 Seguridad](#10-seguridad) · [11 Menores](#11-menores) · [12 Derechos](#12-tus-derechos) ·
[13 Transferencias](#13-transferencias-internacionales) · [14 Cambios](#14-cambios-en-esta-política) ·
[15 Contacto](#15-contacto)

## 1. Quién es el responsable

PinDesk la desarrolla **Max Anthony Mamani Maquera**, desarrollador independiente con domicilio en
Perú (en adelante, «nosotros»). Es el responsable de los datos que se describen en las secciones 2,
5 y 6. Para cualquier asunto de privacidad, escribe a **max.antony.8.5.1@gmail.com**.

## 2. Tu cuenta de Google

PinDesk pide **iniciar sesión con Google**. De tu cuenta recibimos y guardamos:

- tu **dirección de correo** de Google;
- tu **identificador de cuenta de Google** (un número que Google asigna a cada cuenta).

Los usamos para:

- saber qué **plan** tienes (Gratis o Pro) y unir a tu cuenta la licencia que compres;
- llevar la **lista de tus aparatos** (para el límite de 3 de Pro). De cada aparato guardamos un
  identificador generado por PinDesk, su nombre y su sistema operativo, y la fecha en que se
  conectó por última vez;
- **sincronizar por la nube** tus datos entre tus aparatos, si tienes Pro;
- **contestarte** si nos escribes por tu cuenta o un pago.

PinDesk consulta nuestros servidores de vez en cuando para comprobar el estado de tu cuenta y tu
licencia. En esa consulta no va nada de lo que creas.

**Iniciar sesión con Google no da acceso a tu Drive, tu Calendar ni tu correo.** Eso solo ocurre si
conectas tú esos servicios para el asistente (sección 4), y se pide aparte.

Base legal: la ejecución del contrato que aceptas al usar PinDesk (los [Términos](terminos.md)).

## 3. Datos que se quedan en tu aparato

PinDesk guarda en su carpeta de datos (en Windows, `%APPDATA%\PinDesk`, o junto al programa en la
versión portátil; en Android, Mac e iPad, en el espacio privado de la app) lo que tú creas o traes:

- Chats, mensajes, notas, tareas, horarios, recordatorios, lecciones, plantillas y documentos.
- Capturas de pantalla, pines, dibujos, fotos, vídeos, notas de voz y grabaciones de clases o
  reuniones.
- Transcripciones, los temas y lo apuntado de una reunión. **La voz se pasa a texto en tu
  aparato**, con modelos que se ejecutan en él o con el reconocedor de voz del sistema.
- El reconocimiento de texto en imágenes (OCR) y la lectura de PDF, Word, Excel y planos también se
  hacen en tu aparato.
- Tus ajustes.
- Tu **sesión** con Google y las **claves de API** que pegues (por ejemplo, la de TypeSafe o la de
  Brave Search): se guardan **cifradas** con las protecciones del sistema (en Windows, con tu
  usuario de Windows) y nunca en el archivo de ajustes.
- Los reportes de respuestas de la IA que hagas (sección 4).

Nosotros no tenemos acceso a estos datos mientras no salgan de tu aparato por una de las vías de las
secciones 4 y 6.

## 4. Datos que salen de tu aparato

Además de lo de las secciones 2, 5 y 6, algo sale de tu aparato **solo cuando usas una función que
lo necesita**. Ninguna de estas funciones se activa sola. Todo viaja por conexión cifrada
(HTTPS/TLS), y cada servicio trata los datos según su propia política de privacidad. En Windows,
**Ajustes → General → Privacidad y datos** repite esta lista con un botón a donde se enciende o se
apaga cada función.

| Función | Qué se envía | A quién |
|---|---|---|
| **Asistente con IA** ⭐ y **Plantillas con IA** ⭐ | Lo que le escribes, lo reciente de esa conversación y lo que adjuntes (una foto, una captura, el texto de un documento). | El proveedor de IA que elijas en Ajustes → Asistente: **Anthropic** (Claude) o **DeepSeek**. |
| **Resúmenes de transcripciones** ⭐ | El texto de la transcripción (nunca el audio). | El proveedor de IA que elijas. |
| **Jev** ⭐ (urgencia de tareas y temas de una reunión) | Fragmentos de texto (frases ya pasadas a texto en tu aparato, renglones de una nota, tareas) y, en algunas funciones, una imagen, para obtener una clasificación. **Nunca el audio.** | **TypeSafe**, solo con esa función encendida. |
| **Búsqueda web del asistente** ⭐ | Los términos que busca para responderte y la dirección de las páginas que lee. Sin cookies ni datos de tu cuenta. | DuckDuckGo, o Brave Search si pones tu clave de Brave; y la web que se lee. |
| **Conexiones de Google** | Los archivos de Drive que eliges y los eventos del calendario que pides. | Google, solo si conectas esos servicios. Se desconectan desde Ajustes → Asistente. |
| **Voces en línea del lector** | El texto que se lee en voz alta. | Microsoft, solo si eliges una de sus voces en línea; las voces del sistema funcionan sin red. |
| **Compartir por enlace** | El archivo que eliges compartir. | Un servicio público de archivos temporales. Cualquiera con el enlace puede abrirlo hasta que caduque (de horas a días). No lo uses para algo privado. |
| **Descarga de modelos y diccionarios** | Solo la petición de descarga (como en cualquier descarga, el servidor ve tu dirección IP). Nada tuyo. | Los sitios donde se publican esos modelos (por ejemplo, Hugging Face o GitHub). |
| **Enlaces que abres** | Lo gestiona tu navegador o el programa que elijas. | La web o el programa de destino. |

⭐ = función de PinDesk Pro.

**Sobre las peticiones de IA.** No usamos el contenido de tus peticiones de IA para nada más que
darte la respuesta, ni lo guardamos en nuestros servidores. El proveedor de IA lo trata según sus
propias condiciones: revísalas antes de enviarle información sensible.

**Contenido generado por IA.** Las respuestas las genera un modelo de terceros y pueden contener
errores. Puedes informar de una respuesta inadecuada con **Reportar respuesta…** (menú del mensaje
› Más): eliges el motivo, se guarda en tu carpeta de datos y se abre tu programa de correo con el
reporte escrito, para que nos lo mandes si quieres. Solo nos llega lo que tú decidas enviar.

## 5. Pagos

Si compras **PinDesk Pro**, el pago lo procesa un **proveedor de pago** (por ejemplo, la pasarela de
tarjetas, PayPal o Yape, según el medio que elijas). Tus datos de pago (número de tarjeta, cuenta de
PayPal o de Yape) **los recibe y los trata ese proveedor, no nosotros**. **No guardamos los datos de
tu tarjeta.**

Del proveedor de pago recibimos y guardamos solo lo necesario para activar tu licencia, darte
soporte y cumplir nuestras obligaciones legales y contables: el correo de tu cuenta, la modalidad
comprada, el importe, la moneda, la fecha, el país de facturación, el estado del pago (pagado,
renovado, cancelado o reembolsado) y el identificador de la operación.

Base legal: la ejecución del contrato de compra y el cumplimiento de obligaciones legales.

## 6. Sincronización

### Por Wi‑Fi (todos los planes)

Tus aparatos se encuentran por la red local y se emparejan con un código o un QR. Todo lo que viaja
va **cifrado** con una clave que solo conocen tus aparatos, directamente de uno a otro, **sin
servidores intermedios en internet**. Si compartes un chat con otra persona, esa persona recibe una
copia en su aparato.

### Por la nube (Pro)

Si tienes **Pro** y usas la sincronización por la nube, los chats, archivos y cambios que
sincronizas se suben a **nuestros servidores** (alojados en un proveedor de servicios en la nube que
contratamos) para que lleguen a tus otros aparatos, y también a las personas de los **chats
compartidos en la nube** de los que formes parte. Viajan **cifrados** (HTTPS/TLS) y se suben solo
los cambios.

Usamos esos datos **solo para sincronizarlos**: no los miramos, no los analizamos y no los usamos
para nada más. Solo accederíamos a ellos si tú nos lo pides para resolver un problema, o si una ley
o una autoridad competente nos obliga.

Base legal: la ejecución del contrato (el servicio de sincronización que contratas con Pro).

## 7. Lo que no hacemos

- No mostramos publicidad ni usamos identificadores publicitarios.
- No usamos analítica, informes de fallos remotos ni rastreadores. Los registros de la app se quedan
  en tu aparato.
- No vendemos, alquilamos ni cedemos datos personales.
- No usamos tus datos para entrenar modelos de IA. (Los proveedores de IA a los que envías datos
  tienen sus propias condiciones; revísalas.)

## 8. Conservación y borrado

- **En tu aparato**, tus datos se conservan hasta que los borres. En Windows, **Ajustes → General →
  Tus datos, en tu disco** abre la carpeta de datos: cópiala para llevártelos, o cierra PinDesk y
  bórrala para quitarlo todo. Desinstalar PinDesk puede dejar esa carpeta (para no perder tus cosas
  por error); bórrala a mano si quieres. Cómo hacerlo: [Desinstalar](instalar.md#desinstalar).
- **Tu cuenta y tu lista de aparatos** se conservan mientras uses PinDesk. Puedes pedirnos que
  borremos tu cuenta en cualquier momento.
- **Los datos de la nube** se conservan mientras tengas cuenta. Si Pro vence, **no los borramos por
  eso**: la nube se pausa y vuelve a ponerse al día cuando renuevas. Puedes pedirnos que los
  borremos cuando quieras, y los borramos si borras tu cuenta. Las copias de seguridad de nuestros
  servidores se sobrescriben en un plazo de hasta 30 días.
- **Los datos de pago** que guardamos (sección 5) se conservan el tiempo que exige la ley tributaria
  y contable, aunque borres tu cuenta.
- **Lo que enviaste a un tercero** (sección 4) se rige por ese servicio. Los enlaces temporales
  caducan solos.
- **Las copias en tus otros aparatos**, o en los de las personas con quienes compartiste un chat, se
  borran en esos aparatos.

## 9. Permisos y para qué sirven

- **Micrófono**: notas de voz, dictado y grabar clases o reuniones; solo mientras lo usas.
- **Capturar la pantalla**: solo cuando tú lo inicias (una captura, un clip o la grabación de la
  pantalla).
- **Cámara**: solo si la eliges para una foto, un clip o leer un QR.
- **Red**: iniciar sesión, comprobar tu licencia, las funciones de la sección 4 y la sincronización.
- **Notificaciones**: los avisos de tareas, clases y evaluaciones.
- **Arrancar con el sistema**: solo si lo enciendes en Ajustes.

PinDesk no lee tus contactos, tu ubicación ni tus correos.

## 10. Seguridad

Tu sesión y tus claves se guardan cifradas en tu aparato. Las conexiones a internet usan HTTPS y la
sincronización por Wi‑Fi va cifrada entre tus aparatos. Limitamos el acceso a nuestros servidores a
lo imprescindible. Ningún sistema es infalible: protege tu aparato y tu cuenta de Google con
contraseña y, si puedes, con verificación en dos pasos. Si ocurriera un incidente de seguridad que
afecte a tus datos, te lo comunicaremos y avisaremos a la autoridad cuando la ley lo exija.

## 11. Menores

PinDesk no está dirigida a menores de 14 años (ni de la edad mínima que fije la ley de tu país para
dar su consentimiento) y no recoge conscientemente datos de niños. Los menores de esa edad solo
pueden usar PinDesk con el permiso y la supervisión de sus padres o tutores. Las funciones de IA usan
servicios de terceros que pueden exigir una edad mínima mayor. Si crees que un menor nos ha dado
datos sin ese permiso, escríbenos y los borraremos.

## 12. Tus derechos

Según la ley que te aplique (por ejemplo, la **Ley 29733 de Protección de Datos Personales** del
Perú y su reglamento, el **RGPD** en la Unión Europea o la LOPDGDD en España), tienes derecho a
**acceder** a tus datos, **rectificarlos**, **cancelarlos o suprimirlos**, **oponerte** a su
tratamiento y, cuando corresponda, a la **portabilidad**. Los datos que están en tu aparato los
controlas tú directamente. Para los de tu cuenta, la nube o los pagos, escríbenos a
**max.antony.8.5.1@gmail.com** desde el correo de tu cuenta; te contestaremos en los plazos que
fija la ley.

También puedes reclamar ante tu autoridad de protección de datos: en Perú, la **Autoridad Nacional
de Protección de Datos Personales** (Ministerio de Justicia y Derechos Humanos); en España, la AEPD.

## 13. Transferencias internacionales

Nuestros servidores, los proveedores de pago y los de IA pueden estar fuera de tu país (por ejemplo,
en Estados Unidos, la Unión Europea o, si eliges DeepSeek, en China). Al usar esas funciones, tus
datos pueden tratarse allí. Elegimos proveedores que ofrecen garantías adecuadas de protección.

## 14. Cambios en esta política

Si cambiamos esta política, publicaremos la nueva versión en esta misma dirección con su fecha. Si
el cambio es importante, también lo avisaremos dentro de la aplicación antes de que se aplique.

## 15. Contacto

**Max Anthony Mamani Maquera** · Correo: **max.antony.8.5.1@gmail.com**
