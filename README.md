# Colmena

Colmena es una app de escritorio para Windows que junta en un solo lugar lo que un estudiante de la UNLaM tiene en MIeL (Materias Interactivas en Línea): las prácticas, los mensajes de los docentes y sus publicaciones en los foros. Te avisa de las fechas de entrega y te deja entregar trabajos con confirmación previa.

Este repositorio tiene solo los instaladores de cada versión. El código de la app está en un repositorio privado.

- **Descargar:** la última versión está en [Releases](https://github.com/edlazo/colmena-releases/releases/latest).
- **Página:** https://edlazo.github.io/colmena-releases/
- **Política de privacidad:** https://edlazo.github.io/colmena-releases/privacidad.html

## Qué hace

- **Panel:** lo próximo a entregar, las fechas que encontró y lo que llegó desde la última vez que abriste la app.
- **Materias:** de cada materia que seguís, las prácticas con su estado, nota e historial de entregas y correcciones, los mensajes de los docentes, sus publicaciones en los foros y el calendario de la cátedra.
- **Recordatorios:** busca fechas de entrega en las prácticas, los mensajes, los foros y el calendario, y las deja "por verificar" con el texto original. Cuando confirmás una, te avisa 3 días, 1 día y 3 horas antes. También podés crear los tuyos.
- **Avisos de Windows:** mensajes y publicaciones de docentes, prácticas nuevas, correcciones, posibles prórrogas y entregas que se acercan. La app sigue funcionando junto al reloj con la ventana cerrada.
- **Entregas:** elegís el archivo, la app revisa que no esté vacío y que pese hasta 40 MB, muestra todo lo que se va a mandar y te da 10 segundos para deshacer. Después comprueba en MIeL que la entrega haya quedado registrada. Arranca en **modo simulación**, que hace todos los pasos menos el envío: para entregar de verdad hay que apagarlo en Cuenta.
- **Google Calendar (opcional):** las entregas confirmadas se cargan en un calendario "Colmena" de tu cuenta de Google, con sus avisos, para que te lleguen al celular aunque la PC esté apagada.
- **Actualizaciones:** las versiones nuevas llegan solas.

## Cómo funciona

- **Sin servidor.** Cada persona instala la app en su PC y entra con su propia cuenta de MIeL. Nada pasa por un servidor de Colmena: la app habla directo con MIeL y, si lo conectás, con Google Calendar.
- **Lee lo mismo que ves vos.** MIeL no tiene una forma oficial de conectarse, así que la app lee las mismas páginas que abrís en el navegador.
- **Pocas consultas.** Revisa MIeL cada 12 a 28 minutos, entre las 7 y las 23, con pausas en el almuerzo, la merienda y la cena, y nunca de noche. Si no hay nada nuevo, cada vuelta es una sola consulta.
- **Freno de emergencia.** Si MIeL rechaza la contraseña, si hay errores seguidos o si la app pide más de lo normal, se detiene sola. Según el motivo, vuelve sola más tarde o espera a que toques "Reanudar". Así nunca insiste contra tu cuenta.
- **Todo encriptado en tu PC.** El usuario, la contraseña, la sesión y los datos de MIeL se guardan encriptados con la protección de datos de Windows: solo los puede abrir tu usuario de Windows.
- **Leer marca como leído.** Para encontrar fechas, la app abre los mensajes y los temas del foro. En MIeL quedan marcados como leídos, igual que si los abrieras vos.

## Requisitos

- Windows 10 u 11 de 64 bits.
- Una cuenta de MIeL de la UNLaM.
- Conexión a internet.

## Instalar

1. Bajá `Colmena-Setup-<versión>.exe` desde [Releases](https://github.com/edlazo/colmena-releases/releases/latest).
2. Abrilo. Como el instalador no está firmado, Windows puede mostrar "Windows protegió tu PC": tocá **Más información** y después **Ejecutar de todas formas**. Pasa solo en la primera instalación.
3. Seguí el asistente: acuerdo de licencia, carpeta de instalación, acceso directo en el escritorio e inicio con Windows.
4. Abrí Colmena y entrá con tu usuario y contraseña de MIeL.

## Actualizaciones

La app busca versiones nuevas al abrirse y una vez por día, y las baja sola. Cuando una está lista, avisa y muestra el botón **Actualizar**. Si no lo tocás, se instala la próxima vez que salgas de la app. Nunca se instala en medio de una entrega, y conserva tus datos, tu sesión y tus recordatorios.

## Desinstalar

Desde **Configuración → Aplicaciones → Aplicaciones instaladas → Colmena → Desinstalar**. Si querés borrar también tus datos, antes tocá **Cerrar sesión** en Cuenta: borra de la PC el usuario, la contraseña, la sesión y los datos de la cuenta, y si conectaste Google Calendar, lo desconecta y borra el calendario "Colmena".

## Privacidad

- Tus datos quedan en tu PC, encriptados. Colmena no los manda a ningún servidor propio ni los comparte con nadie.
- Los mensajes y foros pueden tener nombres y notas de otros estudiantes: la app no los comparte ni los exporta. De una entrega grupal guarda solo el nombre del grupo.
- Google Calendar es opcional. Si lo conectás, Colmena crea su propio calendario "Colmena" y lee el mail de la cuenta que conectaste, para mostrarte cuál es. No ve ni cambia tus otros calendarios.

El detalle está en la [política de privacidad](https://edlazo.github.io/colmena-releases/privacidad.html).

## Términos y condiciones

Al instalar Colmena aceptás el acuerdo de licencia que muestra el instalador, que es el texto que vale. En resumen:

1. **Proyecto independiente.** Colmena no es de la Universidad Nacional de La Matanza (UNLaM) ni de MIeL, y no está respaldada ni revisada por ellas. "UNLaM" y "MIeL" se nombran solo para decir con qué sistema funciona la app.
2. **Uso personal.** Es para que cada estudiante consulte su propia cuenta de MIeL. Usá solo tu cuenta y cumplí las condiciones de uso de MIeL y de la UNLaM. Sos responsable del uso que hagas de tu cuenta a través de la app.
3. **MIeL es la referencia.** Lo que muestra la app es una copia de lo que hay en MIeL y puede estar desactualizado o incompleto. Las fechas que la app detecta pueden fallar: por eso llegan "por verificar". Revisá siempre los plazos y las entregas en MIeL.
4. **Las entregas no se deshacen.** En MIeL una entrega no se puede borrar ni reemplazar. Antes de confirmar, revisá el archivo, la práctica, el docente y el grupo. Si la app no puede confirmar que la entrega quedó registrada, te lo avisa: en ese caso revisala en MIeL.
5. **Puede dejar de funcionar.** Si MIeL cambia sus páginas, la app puede dejar de leerlas, total o parcialmente, hasta que salga una versión que lo corrija.
6. **Sin garantía.** Colmena se ofrece "tal como está", gratis y sin garantía de ningún tipo. Sus autores no responden por entregas fuera de término o no registradas, plazos que la app no detectó, datos perdidos, bloqueos de cuenta ni ningún otro daño que surja de usarla o de no poder usarla.
7. **Cambios.** Cada versión nueva puede traer un acuerdo actualizado, que reemplaza al anterior.
8. **Ley aplicable.** Se rige por las leyes de la República Argentina.

## Derechos y licencia

© 2026 edlazo y n4hue. Todos los derechos reservados.

Se otorga una licencia gratuita, personal, no exclusiva e intransferible para bajar, instalar y usar Colmena en tus propias computadoras. No se permite copiar, modificar, descompilar, vender, alquilar, redistribuir ni publicar la app o sus instaladores en otro lugar sin permiso escrito de sus autores.

UNLaM, MIeL, Google y Google Calendar son marcas de sus respectivos dueños.

## Contacto

Para consultas, escribile a [edlazo](https://github.com/edlazo) o a [n4hue](https://github.com/n4hue) en GitHub.
