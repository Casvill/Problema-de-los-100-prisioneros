# Problema-de-los-100-prisioneros

El dilema de los 100 prisioneros y 100 cajones es un problema en la teoría de la probabilidad y la combinatoria. Consiste en que cada uno de 100 prisioneros debe encontrar su número en uno de los 100 cajones para sobrevivir y si alguno no lo encuentra, todos morirán; y, cada prisionero puede abrir sólo 50 cajones y no puede comunicarse con los demás prisioneros, excepto en el debate previo de la estrategia.  
### Enunciado:
El director de una prisión ofrece a un centenar de condenados a muerte (numerados del 1 al 100) una última oportunidad. En una sala hay un armario con 100 cajones. El director coloca aleatoriamente en cada cajón uno de los números de 1 a 100. Los prisioneros entran en la sala, uno tras otro. Cada uno de los prisioneros puede: abrir y comprobar sólo 50 cajones en cualquier orden, y después cierra todos los cajones. Si en esta búsqueda todos los prisioneros han encontrado respectivamente su número, todos los prisioneros son perdonados; si un prisionero no encontrara su número, todos los prisioneros serán ejecutados. Antes de que el primer prisionero busque su número, los prisioneros pueden discutir la estrategia, pero no pueden comunicarse a partir de este momento. ¿Cuál es la mejor estrategia de los prisioneros?   
### Solución:

Sorprendentemente existe una estrategia que proporciona la probabilidad de supervivencia de más del 30%. La clave del éxito radica en el hecho de que los prisioneros no necesitan decidir de antemano cuáles cajones abrir: cada prisionero puede utilizar la información recibida del contenido de los cajones ya abiertos, para decidir cuál abrir después. Otra importante observación es que el éxito de un prisionero no es independiente del éxito de otros prisioneros, ya que todo depende de cómo se distribuyeron los números en los cajones.

La estrategia descrita cubre no sólo los prisioneros, sino también los cajones numerados del 1 al 100 (por ejemplo, hilera por hilera, a partir del primer cajón de la esquina superior izquierda del armario). La estrategia a seguir es:

- Cada prisionero, primero abre el cajón con su número.
- Si este cajón contiene su número, el prisionero ha concluido con éxito.
- En caso contrario, el cajón contiene un número de otro prisionero, y se abre el cajón con dicho número.
- El prisionero repite los pasos 2 y 3 hasta que encuentre su número o hasta abrir los 50 cajones.

Comenzando con su propio número el prisionero se garantiza de seguir una secuencia de apertura de cajones en el que pueda eventualmente encontrar su número. La única cuestión reside en si la secuencia es mayor de 50.  

![Wikipedia](https://es.wikipedia.org/wiki/Problema_de_los_100_prisioneros)
