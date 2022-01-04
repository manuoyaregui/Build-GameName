# Just Neon, but Everywhere

### Por *Salvador Matías* y *Oyaregui Manuel*

La finalidad de este archivo es otorgar información sobre el juego desarrollado, incluyendo mecánicas implementadas y por implementar, y posibles cambios a realizar a futuro.

*Última fecha de edición del documento: 04/01/2022*

----------------------------------------

## Resumen del juego

El juego desarrollado trata de un arcade, donde manejamos un protagonista que tiene que huir de la desintegración de un mundo generado en su cabeza, gracias al consumo excesivo de estupefacientes alucinógenos. 

El protagonista debe lograr la mayor distancia posible antes de que sea consumido por la desintegración, o eliminado por sus enemigos. Este juego será diseñado para que la mayor dificultad sea ser lo suficientemente ágil para sobrepasar los obstáculos.

----------------------------------------

## Controles

Los controles están definidos de una forma tradicional, donde:

- **W A S D** = movimiento del personaje
- **Click Izquierdo** = disparo del arma
- **Barra espaciadora** = salto (puede realizar doble salto)
- **Movimiento del mouse** = control de la cámara
- **Left Shift** = Dash

----------------------------------------

## Player

- Podrá saltar sobre paredes.
- Disparará a enemigos.
- Posee una escopeta que generará un recoil de sentido contrario de donde esté mirando.
- Podrá obtener un escudo disparando o tocando el respectivo PowerUp, el cual bloqueará 1(uno) de daño y luego se destruirá.
- Podrá obtener balas tocando el respectivo PowerUp.
- Si pasa una x cantidad de tiempo sin tocar el piso, obtendrá un multiplicador de puntuación, que va desde x2 a x4, y una bonificación de velocidad. Si vuelve a tocar el piso, comenzara a perder estas bonificaciones.

----------------------------------------

## Enemigo Básico

- Disparará al jugador si este se encuentra en su rango de visión.
- Si recibe un disparo de cualquier fuente, éste muere.

----------------------------------------

## Super Enemigo

- No recibe daño.
- Va ligeramente más rápido que el jugador en su velocidad base.
- Al tocarlo, el jugador muere, y termina el juego.
- Cuanta más distancia haya entre el jugador y éste, el super enemigo irá más rápido. 

----------------------------------------

## Cosas a Agregar / Cambiar:

- Una especie de barril explosiv o similar.
- Buffear a los enemigos (actualmente, solo puede matar al jugador si está
quieto).
- Buffear el escudo (dado que el enemigo casi nunca te va a matar, el escudo es
prácticamente inútil).
- Más variedad de enemigos.
- Implementar un shop y un sistema de monedas.
- Implementar un sistema de progresión de dificultad.
- Incluir más objetos recolectables.
- Implementar algún sistema de guía intuitiva para el jugador (las guías actuales.
no son muy efectivas).
- (a definir) que se puedan modificar las skins del juego, tales como apariencia
de los enemigos, del main enemigo, de las armas, efectos de colores. Estas se
podrán conseguir en el shop, usando las monedas obtenidas durante el juego.
- Implementar opciones de accesibilidad (ej: para personas con daltonismo,
problemas epilépticos, etc.).
- (a definir) crear un modo de juego que tenga la variante de que el jugador no
controla el movimiento, es decir, solo se mueve para adelante, el jugador
controla las armas, el salto, la cámara.
- Agregar gameblocks con algún movimiento.

----------------------------------------

## Bugs/errores por solucionar

- Si intentas moverte durante la cinemática al comienzo del juego, puede que
comiences en otro lugar luego de finalizar la misma.
- En el tutorial hay algunas zonas donde si caes al vacío te quedas “trabado”. 
- En algunos casos, las balas atraviesan las paredes.

----------------------------------------
