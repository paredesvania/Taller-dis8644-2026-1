# sesion-07a

## Antes de la Solemne

### Cuando dije en la bitácora anterior que supimos manejar el estrés, era broma, no sabemos. 

**Antes del desastre:**

La clase comenzó con una introducción sobre el flujo de trabajo post-solemne y una charla sobre la fabricación de placas PCB (mencionando la accesibilidad de mandarlas a producir a China). Posteriormente, se definieron los lineamientos para la próxima sesión solemne, donde se solicitó que un integrante por grupo aprendiera técnicas de soldadura para fijar componentes críticos y mejorar la solidez del diseño final.

------
**Desastre**

Mientras parte Santiago se enfocaba en la soldadura, Kriss y yo nos dedicamos a evaluar el modelo de la carcasa. Analizamos las prioridades desde la Experiencia de Usuario (UX), intentando resolver problemas que quizas a nosotras mos molestarian al ocuparlo. Aunque se probó un prototipo inicial de caja e incluso se integró un implemento impreso en 3D para mejorar el agarre de las palancas, nos enfrentamos a problemas de dimensiones que impedían que los botones encajaran correctamente pero decidimos poner un pequeño piso y no complicarnos.

La sesión dio un giro crítico al detectar un cable suelto en la protoboard. No sabiamos cual era la   ubicación original (sospechando inicialmente de un puente entre placas) esperamos la revisión en conjunto con Santiago. Tras analizar el circuito, descubrimos que el cable no pertenecía a la posición intuida. Al probar el sistema, el dispositivo ya no funcionaba como el día anterior; perdimos la calidad del sonido y la respuesta de los botones.

Revisamos el sistema y lo harmamos de la forma inicial para ver fue algo que no conectamos bien al momento de conectar cables.

![p1-intento](https://github.com/paulafuentesm/dis8644-2026-1/blob/e4aa47c4b28daf7b4425c55b719db6587b777187/13-paulafuentesm/sesion-07a/imagenes/p1-intento.jpg)
pd: el raton (yo) aprieta el puño de la rabia. (meme)

![p1-intento](https://github.com/paulafuentesm/dis8644-2026-1/blob/e4aa47c4b28daf7b4425c55b719db6587b777187/13-paulafuentesm/sesion-07a/imagenes/p2-intento.jpg)
imag: aqui nos dividimos para ver por partes cuales podia ser el problema, aqui estan los ultimos 2 modulos.

![p1-intento](https://github.com/paulafuentesm/dis8644-2026-1/blob/e4aa47c4b28daf7b4425c55b719db6587b777187/13-paulafuentesm/sesion-07a/imagenes/p3-intento.jpg)
imag: aqui esta los primeros 2 modulos, revisando DONDE ESTABA EL ERROR, QUE PASO, un misterio.

Entramos todos en un estado de estrés brigido al no poder identificar la falla mediante la revisión visual. Procedimos a desarmar y probar individualmente los módulos del 555 y el 4017; aunque funcionaban de forma aislada, el sistema integrado seguía sin responder. Tras una hora de frustración y agotamiento mental, tomamos la decisión más difícil pero necesaria para asegurar la fiabilidad del proyecto: desarmar el circuito por completo y reconstruirlo desde cero, priorizando la metodología y el orden para recuperar la funcionalidad perdida.

#### Ultima etapa y conclución: aceptación
![p1-intento](https://github.com/paulafuentesm/dis8644-2026-1/blob/e4aa47c4b28daf7b4425c55b719db6587b777187/13-paulafuentesm/sesion-07a/imagenes/p4-desarme.jpg)



https://github.com/user-attachments/assets/a4aef82f-ded5-4994-88cc-8c07691dace7


