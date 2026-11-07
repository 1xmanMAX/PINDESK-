# Instalar PinDesk en Windows

[← Volver al inicio](../README.md)

Instalar PinDesk lleva un par de minutos y **no necesita permisos de administrador**: se instala
solo para tu usuario de Windows.

**Necesitas**: Windows 10 versión 21H2 o posterior, o Windows 11, de 64 bits, y una cuenta de Google
para iniciar sesión.

Contenido: [Instalar](#instalar-paso-a-paso) · [SmartScreen](#si-windows-dice-windows-protegió-su-pc) ·
[Primer arranque](#el-primer-arranque) · [Actualizar](#actualizar) ·
[Desinstalar](#desinstalar) · [Versión portátil](#versión-portátil) ·
[Problemas comunes](#problemas-comunes)

## Instalar, paso a paso

1. **Descarga el ZIP**:
   [PinDesk-Windows-x64.zip](https://github.com/1xmanMAX/PINDESK-/releases/latest/download/PinDesk-Windows-x64.zip).
   Siempre es la última versión. Normalmente se guarda en tu carpeta **Descargas**.
2. **Extrae el ZIP**: en el Explorador de archivos, haz **clic derecho** sobre
   `PinDesk-Windows-x64.zip` → **Extraer todo…** → **Extraer**. Se abre una carpeta nueva con los
   archivos de PinDesk.

   > [!IMPORTANT]
   > No abras los archivos directamente desde dentro del ZIP (con doble clic sobre el ZIP).
   > Windows los saca de uno en uno a una carpeta temporal y PinDesk no encuentra sus piezas.
   > Extráelo siempre primero.

3. **Abre `Instalar.cmd`** con doble clic, **desde la carpeta extraída**. Se abre un momento una
   ventana negra que:
   - copia PinDesk a `%LOCALAPPDATA%\Programs\PinDesk`;
   - crea los accesos **PinDesk** y **PinDesk Plantillas** en el menú Inicio;
   - y abre PinDesk.
4. Listo. PinDesk se queda en la **bandeja del sistema** (junto al reloj). Ya puedes borrar el ZIP
   y la carpeta extraída si quieres.

Opcional: en **Configuración de Windows → Aplicaciones → Aplicaciones predeterminadas** puedes
elegir PinDesk para abrir fotos, vídeos, audios o PDF.

## Si Windows dice «Windows protegió su PC»

Es el filtro **SmartScreen** de Windows. Sale con los programas que se descargan de internet y que
todavía no tienen muchas descargas. Para seguir:

1. Pulsa **Más información**.
2. Comprueba que el archivo es `Instalar.cmd` o `pindesk.exe`.
3. Pulsa **Ejecutar de todas formas**.

Puede salir una o dos veces (para `Instalar.cmd` y para la primera vez que se abre PinDesk). Después
ya no vuelve a preguntar.

> [!NOTE]
> Descarga PinDesk **solo desde esta página** (`github.com/1xmanMAX/PINDESK-`). Si alguien te pasa
> el ZIP por otro lado, no podemos garantizar que sea el original.

## El primer arranque

1. **Inicia sesión con tu cuenta de Google.** Sigue los pasos para elegir tu cuenta y dar tu
   permiso. Con eso tienes el plan gratuito. Si tienes PinDesk Pro, se activa
   solo con la misma cuenta (ver [Planes](planes.md)).
2. **Permiso de red.** La primera vez Windows puede preguntar si PinDesk puede usar la red. Pulsa
   **Permitir** (al menos en redes privadas): sin ese permiso, tus otros aparatos no encuentran este
   PC para sincronizar.
3. Prueba la captura con `Ctrl Alt X`, o haz clic en el icono de PinDesk de la bandeja.

## Actualizar

1. Descarga el ZIP nuevo con el mismo enlace de siempre:
   [PinDesk-Windows-x64.zip](https://github.com/1xmanMAX/PINDESK-/releases/latest/download/PinDesk-Windows-x64.zip).
2. Extráelo y abre `Instalar.cmd`, igual que la primera vez.

`Instalar.cmd` cierra PinDesk si estaba abierta, cambia los programas por los nuevos y la vuelve a
abrir. **Tus datos no se tocan**: chats, tareas, capturas, ajustes y tu sesión siguen igual.

Si tenías **PixPin Max** (el nombre anterior de PinDesk), `Instalar.cmd` la sustituye y tus datos
pasan a PinDesk la primera vez que se abre.

## Desinstalar

1. Si encendiste **Arrancar con Windows**, apágalo antes en PinDesk: **Ajustes → General**.
2. **Cierra PinDesk**: clic en su icono de la bandeja → **Salir**.
3. **Borra la carpeta del programa**: pega `%LOCALAPPDATA%\Programs\PinDesk` en la barra de
   direcciones del Explorador, pulsa Intro, sube un nivel y borra la carpeta **PinDesk**.
4. **Borra los accesos del menú Inicio**: pega
   `%APPDATA%\Microsoft\Windows\Start Menu\Programs` en el Explorador y borra **PinDesk** y
   **PinDesk Plantillas**.

Así se quita el programa, pero **tus datos se quedan** en `%APPDATA%\PinDesk`, por si vuelves o
quieres copiarlos. Si quieres borrarlo todo, borra también esa carpeta (con PinDesk cerrada). Lo que
haya en tus otros aparatos, o en la nube si tienes Pro, se gestiona aparte: lo explica la
[Política de privacidad](privacidad.md#8-conservación-y-borrado).

## Versión portátil

Si quieres llevar PinDesk en un USB: copia la carpeta extraída donde quieras y crea junto a
`pindesk.exe` un archivo vacío llamado `pindesk.toml`. Con ese archivo al lado, PinDesk guarda todo
en esa misma carpeta y nada en el resto del equipo. Ábrela con `pindesk.exe`.

## Problemas comunes

### «Windows no puede encontrar pindesk.exe»

Casi siempre significa que **se abrió desde dentro del ZIP**, sin extraerlo. Vuelve al ZIP, haz clic
derecho → **Extraer todo…**, entra en la carpeta extraída y abre `Instalar.cmd` desde ahí.

Si `Instalar.cmd` dice **«No encuentro pindesk.exe junto a Instalar.cmd»**, es lo mismo: extrae el
ZIP primero.

### «No se pudo copiar PinDesk»

PinDesk seguía abierta y Windows no dejó cambiar sus archivos. Ciérrala desde la bandeja
(**Salir**); si no aparece, ciérrala en el Administrador de tareas (`Ctrl Mayús Esc`). Después
vuelve a abrir `Instalar.cmd`.

### El antivirus borra o bloquea un archivo

Algunos antivirus desconfían de los programas nuevos. Restaura el archivo desde la cuarentena de tu
antivirus y añade una excepción para la carpeta `%LOCALAPPDATA%\Programs\PinDesk`. Si te pasa,
cuéntanoslo en un [informe de fallo](https://github.com/1xmanMAX/PINDESK-/issues/new/choose) y di qué
antivirus usas.

### Windows 11 bloquea la app y no ofrece «Ejecutar de todas formas»

Puede ser **Control inteligente de aplicaciones** (Seguridad de Windows → Control de aplicaciones y
del navegador). Si está activado, bloquea los programas que aún no reconoce. Cuéntanoslo en un
[informe de fallo](https://github.com/1xmanMAX/PINDESK-/issues/new/choose) para poder ayudarte.

### No me deja iniciar sesión con Google

- Comprueba que tienes internet y que la hora de Windows es correcta (Configuración → Hora e
  idioma → **Sincronizar ahora**).
- Si el inicio de sesión se abre en tu navegador y no ves la página, abre tu navegador
  predeterminado una vez y vuelve a intentarlo.
- Si usas una cuenta de Google de trabajo o de un centro de estudios, puede que su administrador no
  permita iniciar sesión en apps externas. Prueba con una cuenta personal.

### Mis aparatos no se encuentran para sincronizar por Wi-Fi

- Los dos tienen que estar en **la misma red Wi‑Fi** (no en una red de invitados que aísla a los
  aparatos).
- Si en el primer arranque cerraste el aviso de red sin pulsar **Permitir**, Windows bloquea a
  PinDesk. Arréglalo en **Seguridad de Windows → Firewall y protección de red → Permitir una
  aplicación a través del firewall → Cambiar la configuración**, y marca **PinDesk** en **Privada**.
- En Windows, la red Wi‑Fi debe estar como **red privada** (Configuración → Red e Internet → tu
  Wi‑Fi → Tipo de perfil de red).

### Algunas fotos o vídeos no se abren (HEIC, AVIF, JPEG XL, WebM…)

Esos formatos necesitan una extensión gratuita de Microsoft Store (HEVC, AV1, VP9 o JPEG XL).
PinDesk te dice cuál falta y cómo instalarla.

### Otra cosa

Revisa las [Preguntas frecuentes](preguntas.md). Si no está ahí, abre un
[informe de fallo](https://github.com/1xmanMAX/PINDESK-/issues/new/choose): cuanto más detalle nos des
(versión de Windows, qué hiciste y qué pasó), antes lo arreglamos.
