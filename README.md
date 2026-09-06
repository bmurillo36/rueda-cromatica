# Rueda cromatica

Menu radial giratorio inspirado en la rueda de color de Concepts (iPad):
un disco anclado en la esquina superior izquierda del que solo se ve el
cuarto inferior derecho, porque el resto queda fuera de la pantalla.

Proyecto independiente. No forma parte del Monitor: el contenido de fondo
(cursos, correo, docentes) es solo una maqueta para ver la estetica en uso.

## Como funciona

- El boton MENU abre y cierra la rueda.
- Cuatro anillos cromaticos giran en sentido horario a velocidades distintas.
- El anillo de secciones se arrastra con el dedo a izquierda o derecha:
  150 px equivalen a una seccion. Al soltar hay inercia y encaje automatico.
- Un puntero fijo a 45 grados marca la seccion activa; al cambiar, cambian el
  titulo, la descripcion y el color de acento de toda la interfaz.
- Los rotulos se recalculan en cada fotograma fuera del grupo que rota, de
  modo que siempre se leen en horizontal.
- Tambien responde a la rueda del raton y a las flechas del teclado.

## Como se prueba

Un solo fichero, sin dependencias ni servidor: abrir `index.html` en el
navegador. Las tipografias Barlow se cargan de Google Fonts y, sin conexion,
caen a la del sistema.

## Estado

Prototipo de estetica, 06/09/2026. Falta decidir si el color elegido a mano
manda siempre por encima del color de la seccion activa.
