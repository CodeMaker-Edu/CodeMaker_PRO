**Ejercicio 1. Pruebas.**

Botón A enciende los leds, botón B los apaga, el joystick arriba-abajo cambia de color. Se muestra información del color en todo momento en pantalla. Joystick central emite un sonido.

**Ejercicio 2. Cuenta atrás.**

- El joystick arriba-abajo permite configurar un tiempo en segundos (se va viendo en pantalla), y el botón B hace que comience el temporizador.
- Al iniciarse la cuenta atrás, todos los LEDs de Cyberpi están encendidos, y van apagándose proporcionalmente a los segundos, quedando todos apagados al llegar el tiempo a 0.
- Cuando finaliza el tiempo se emite un sonido, un mensaje en pantalla y una animación de LEDs.

**Ejercicio 3: El clásico siguelíneas.**

Programa tu mBot2 para que siga la línea sin salirse. No tiene que hacer nada más que seguir la línea indefinidamente. Cuando lo tengas, no borres esta programación, pues te hará falta para los siguientes ejercicios (es recomendable copiar la programación a un bloc de notas para ir usándola en los siguientes ejercicios).

**Ejercicio 4: Siguelíneas avanzado.**

Añade a mBot2 las siguientes capacidades mientras realiza un siguelíneas.

Funcionalidad 1: detección de obstáculos.
- Si detecta un obstáculo, se dará la vuelta y continuará por la línea en sentido contrario al que venía.

Funcionalidad 2: adapta el siguielíneas para que comience a velocidad 50, pero con cada pulsación del joystick pase lo siguiente:
- Pulsación hacia arriba: aumenta 10 de velocidad (sin llegar a pasarse de 100).
- Pulsación hacia abajo: disminuye 10 de velocidad (sin llegar a bajar de 0).
- Pulsación hacia un lado: el robot da una vuelta 360º hacia ese lado, y continúa si siguelíneas.
- Pulsación central: el robot se para durante unos segundos, emite sonidos y juegos de luces, y continúa su siguelíneas.
(Debe mostrar en todo momento en la pantalla la velocidad a la que va)

**Ejercicio 5: El robot que te sigue.**

Programa a mBot para que siga siempre al objeto que tenga delante (puedes hacer pruebas con una caja). Mientras la detecte, seguirá avanzando, pero cuando deje de detectarla deberá saber por qué lado se ha ido y encontrarla para continuar siguiéndola.

Optimiza los movimientos del robot para tratar de evitar que de vueltas completas buscando al objeto a seguir.

**Ejercicio 6: El robot giratorio.**

Programa a mBot para que se coloque en un punto fijo y vaya girando sobre sí mismo tratando de encontrar los obstáculos que le rodean. Cuando encuentre uno, deberá avanzar hasta tocarlo (no puede empujarlo, debe tocarlo levemente) y volver justo al punto donde estaba, para continuar con sus giros. En la pantalla irá mostrando cuántos objetos ha tocado.
