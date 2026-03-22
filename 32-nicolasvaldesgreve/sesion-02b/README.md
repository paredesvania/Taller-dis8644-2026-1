# sesion-02b

# Apuntes clase 20/03

Se nos entregó el chip NE555P, el cual es un circuito integrado (IC) que se utiliza para generar pulsos, temporizadores y oscilaciones. Éste chip tiene 8 patitas, las cuales se pueden enumerar guiándose ya sea por la dirección del texto, por el punto que puede tener el mismo texto, o por el espacio de medio círculo que tiene el chip, el cual siempre va a la izquierda. Luego de identificar el texto o el espacio que tiene el chip, se cuenta empezando desde la patita de abajo en la izquierda, continuando en sentido antihorario como se muestra en la siguiente imagen:

![Dibujo de chip NE555P](./imagenes/ne555.jpg)

---

### Capacitor de 10μF

El primer capacitor que conectamos fue el de 10μF, ya que ese es el que se indica en el circuito que se dibujó en la pizarra. Al momento de conectar la batería a la protoboard pensé que iba a ser inmediato el parpadeo del LED, por lo que cuando se tardó un poco en reaccionar pensé que me había equivocado, pero luego de unos pocos segundos se emepzó a comportar como se puede ver en el GIF.

![Capacitor de 10μF](./imagenes/capacitor-10.gif)

---

### Capacitor de 100μF

Se nos indicó reemplazar el capacitor de 10μF por el de 100μF, y al momento de intercambiarlo volví a pensar que había hecho algo mal porque la luz del LED se mantuvo prendida por más de lo que pensé que iba a durar, pero luego entendí que solo era porque el capacitor aumentó el tiempo en el que dura encendido el LED, al igual que el tiempo de apagado.

![Capacitor de 100μF](./imagenes/capacitor-100.gif)

---

### Capacitor de 1μF

Luego probamos cambiando el de 100μF al de 1μF, y al momento de conectar el capacitor de 1μF no logré notar ningún cambio en el LED a simple vista, por lo que pensé que sólo se quedaba prendida sin parpadear, pero al momento de grabarlo me di cuenta de que en la cámara del celular si se notaba como la luz se prendía y se apagaba a gran velocidad.

![Capacitor 1μF](./imagenes/capacitor-1.gif)
