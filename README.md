# Nombre de tu escena Fábula Pedrito y el Lobo (index.html)

Joaquin Sahonero · Realidades Extendidas y Experiencias Inmersivas · UGM · 2026

## 1 · Qué es

Una experiencia que busca ver el peso de las decisiones y las oportunidades que tenemos de tener una decisión correcta

- Palabra que busco transmitir: Honestidad

## 2 · Cómo se usa

- Enlace a la escena: https://joaquinsahonero.github.io/fabula_final/
- Dispositivo pensado: computador / teléfono
- Al entrar: qué hace el visitante primero llega a la pradera donde ve a una oveja y puede recorrer la pradera, el objetivo es medir que tan bien corre la página y si los tiempos de carga son los correctos conforme vaya cargando más elementos y los vaya posicionando dentro de la escena.

## 3 · Cómo está hecha

- Herramienta: A-Frame, publicado en GitHub Pages.
- Archivos que usé:

| Archivo | Qué es | De dónde salió | Licencia |
|---|---|---|---|
| assets/models/silla.glb | Modelo 3D | proporcionado por el docente
| assets/models/oveja.glb | Modelo 3D | descargado de la web Cgtrader https://www.cgtrader.com/free-3d-models/animal/mammal/low-poly-cartoon-sheep
| assets/models/balde.glb | Modelo 3D | descargado de la web Cgtrader
| assets/models/saco.glb | Modelo 3D | descargado de la web Cgtrader
| assets/models/barril.glb | Modelo 3D | descargado de la web Cgtrader
| assets/audio/ambiente.mp3 | Sonido ambiente | Pixabay
| assets/audio/oveja.mp3 | Sonido al click | Pixabay

## 4 · Decisiones

- Qué decidí y por qué 
Decidí realizar un montaje simple para esta instancia para testear la relación de espacio dentro de la escena y tener los elementos preparados para realizar la prueba de que tan bien carga la página según los elementos y seguir los parámetros del presupuesto planteado en la solemne 1, en cuanto a materiales estoy probando cosas para ajustar correctamente los valores para poder marcar la ambientación que necesito, de momento tengo pocos elementos para ajustar el posicionamiento de elementos.
Esto es principalmente porque me veo obligado a optimizar en mayor medida un modelo nuevo de una granja ya que en blender no pude lograr agilizar el proceso de optimizado.
- Qué cambió respecto de lo que propuse en la Solemne 1, y por qué.
Principalmente la calidad de los modelos, veo que es bastante interesante el reducir los polígonos y acotar algunas de las espectativas del look visual de la escena para que pueda efectivamente ser cargado y correr sin problemas, veo que los materiales serán mucho más simples de lo que pensaba y debo ajustarlos para no perder mucho detalle para mantener la ambientación.

## 5 · Testing

Video del recorrido: https://ugmchile-my.sharepoint.com/:v:/g/personal/francisco_sahonero_estudiante_ugm_cl/IQAGlvAYjl9jRYGyqF0TweykAd1hooBEWWewv3aKj-ww_s4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Gk1baR

| Prueba | Resultado | Ajuste que hice |
|---|---|---|
| Abrir el enlace en ventana privada | Carga sin quedar en blanco. | Abre correctamente, pero no reproduce el audio ambiental
Al ejecutarse en Pc abre sin problemas | revisar el código para ver si efectivamente fue cargado correctamente el audio
| Dispositivo elegido | PC/ teléfono | ejecutó efectivamente en teléfono no se hicieron pruebas | es necesario revisar si corre bien en teléfono
| Interacciones, una por una | Los objetos responden para poder identificarlos correctamente dentro de la escena, falta generar las interacciones complejas | falta generar las interacciones complejas para el usuario y poder guiarlo correctamente |
| Sonido con audífonos | El sonido de la oveja suena correctamente pero el sonido ambiental no se reproduce. | corregir el código para que se reproduzca efectivamente cuando incia la escena | revisar también el encoding del audio para salir de dudas.
| Fluidez del recorrido | La escena se reproduce de manera fluida | debido a los pocos objetos la carga no es muy demandante para la escena |
| Entrar como si fuera la primera vez | no se entiende que es lo que hay que hacer | No hay interacciones planteadas, solo existe la interacción de la oveja y unas rotaciones de objetos. |

## 6 · Uso de IA

- Qué le pedí a la IA:
Para este apartado le pedí a claude que me asistiera con encontrar errores de código al momento de ver problemas dentro de la escena, ajustando el código que generalmente eran problemas de sintaxis que a simple vista no me percaté al momento de escribir el código, además me ayudo a generar un script para revisar los materiales si contienen el metallness y el rough bien ajustado para evitar problemas de visualización de los modelos.
Para optimizar el trabajo le pedi a claude AI ayuda para la escritura del código y la generación del corral de ovejas a partir de un GLB cargado dentro del repositorio.
- Qué hice yo y qué cambié de lo que me entregó.
Principalmente al ser una forma de corregir mis códigos claramente fuí arreglando los problemas de sintaxis y el script para poder reconocer problemas de shading de los modelos.
Las decisiones artísticas y de composición se mantienen junto con el trabajo de la narrativa de la experiencia.

## 7· Pendientes para el examen (act 25-11-26)

MVP corral de ovejas (genera bastante ambiente y ayuda con la inmersión)

- Lo que falta, en orden de importancia.

1. Mejorar la ambientación con modelos extra y sonidos
2. Corregir la transparencia del saco de alimento
3. Generar el apartado de interacción con el usuario
4. Corregir la narrativa de la interacción para poder integrarla al montaje
5. Generar el código para seguir la línea narrativa para el montaje final
6. Integrar textos para ayudar al usuario a guiarlo por la experiencia
7. Generar 3 estados de decisión para el usuario entre mentira y verdad
8. Generar los resultados dependiendo de los 3 momentos de decisión dentro de la experiencia
9. generar un cierre de la experiencia dependiendo del resultado
