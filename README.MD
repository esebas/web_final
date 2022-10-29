# Comentarios:

## Ajustes de Entrega 1:
- Se sacó el section en el footer.

Respecto a la entrega inicial se agregó:

-Responsive con breakpoint 520px, 768px y 1200 px
-Grid para alinear las cajitas con info en cada resolucion
-Efecto hover y transicion
-Ajuste de textos por breakpoints dependiendo de texto
-Inicio cubriendo nav
-Nav responsive
-Versionado en Github
-etc

## Ajustes por feedback de entrega 2:

```python
- Hay scroll horizontal, esto es debido a que en el navbar tenes "width: 100vw" y position: absolute en el mismo. Una forma de solucionarlo quizás es reemplazando el width: 100vw a width: 100% y el position: relative en el body agregarlo.
NOTA SE: era el with de nav. Solucionado

- Separa un poco más los elementos entre si, ya que están como muy 'pegados'. OK

- Cuidado al utilizar width & height con medidas como vh/vw grandes, puede traer complicaciones en el responsive y/o producir scroll horizontal. OK, solucionado

- Si tenes en el reset "margin: 0, padding:0 ,etc." no es necesario agregar en el body nuevamente "margin: 0".
Nota SE: ok, eliminado.

- No utilices padding/margin con medidas como vh/vw/% y mucho menos si son medidas grandes, puede traer complicaciones en el responsive.
Nota SE: Se cambiaron segun sugerencias

- Cuando tengas que utilizar "cajas" vacías, te recomiendo usar Grid y no flex, ya que es más fácil manejar este tipo de casos con Grid.

- Recorda que el h1 Solo debe contener texto y no un enlace dentro (un elemento "a").
```

## Ajustes para Entrega 3:
```python
- Se agrego sasss y carpetas segun metodologia explicada.

- Uso de variables

- uso de _pages.scss para organizar los estilos

- ajuste y alineamiento de cajas contenedoras

- Breakpoints con mixins

- mixins, include, nesting, etc para reducir y simplificar el código
```