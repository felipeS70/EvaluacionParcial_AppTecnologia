# EvaluacionParcial_AppTecnologia

# TechZone - App de Tecnología

Esta aplicación es un prototipo visual diseñado para una plataforma de ventas de productos tecnológicos. El objetivo principal es mostrar una interfaz intuitiva donde el usuario pueda visualizar un producto, ver su calificación y realizar acciones rápidas como agregar al carrito o consultar especificaciones técnicas.

## App terminada 

<img width="703" height="1478" alt="image" src="https://github.com/user-attachments/assets/7f3f6acb-4fb3-43ce-ac6b-59a3c93a4f3a" />

Esta es la interfaz final ejecutándose en el emulador. Se puede apreciar la jerarquía visual donde resalta el producto y los botones de acción están posicionados en la parte inferior para facilitar el alcance con el pulgar.

## Plantilla 

<img width="687" height="1221" alt="image" src="https://github.com/user-attachments/assets/a12295f9-5585-43ee-ba67-e92f8a67d78f" />

Se utilizó el editor de Android Studio para estructurar los elementos dentro de un contenedor principal, asegurando que el diseño sea limpio y centrado.

## Maqueta

<img width="695" height="1223" alt="image" src="https://github.com/user-attachments/assets/ea3e3802-ce74-492b-943f-998cfbbf2009" />

La vista de planos (Blueprint) permite verificar los márgenes y el espaciado de los componentes (padding y constraints) para asegurar que no existan elementos encimados.

# Sustentación de elementos y atributos usados

Para la construcción de esta interfaz se utilizaron los siguientes componentes de Android XML:

## Imagen (ImageView)

<img width="451" height="420" alt="image" src="https://github.com/user-attachments/assets/1689b670-491e-4cce-ae41-c325c409de37" />

Atributo android:src: Define la fuente de la imagen del producto. 

Atributo android:layout_width y height: Se ajustaron dimensiones fijas para mantener la proporción del producto tecnológico (tamaño de la imagen del producto).

## Texto (TextView)

<img width="549" height="214" alt="image" src="https://github.com/user-attachments/assets/823e15de-0971-497d-a421-f0f52e96016e" />

Atributo android:textSize: Se asignó un tamaño de 24sp para el título y 16sp para la descripción, creando una jerarquía de lectura.

Atributo android:textColor: Se cambió el color del titulo a rojo y el subtitulo que es la descripción a un color azul.

Atributo android:textStyle: Se usó bold en el nombre del producto para darle énfasis y para la descripción en cursiva.

## Input (EditText)

<img width="205" height="32" alt="image" src="https://github.com/user-attachments/assets/72c5e7b9-461f-4121-a847-e0f90df2aa5d" />

Atributo android:hint: Se utilizó "Ingresar correo electrónico" como texto sugerido que desaparece al escribir.

Atributo android:textColorHint: Se aplicó un color gris suave para que el usuario entienda que es un campo de entrada.

## Widget (RatingBar)

<img width="205" height="48" alt="image" src="https://github.com/user-attachments/assets/c3a21551-a035-4f30-97dd-fb1a656e3fab" />

Atributo android:numStars: Se configuró en 5 estrellas para mostrar la valoración del producto.

Personalización: Se ajustó el color en amarillo del widget para resaltar la calificación positiva del equipo tecnológico (ProgressTint).

## Botones (Button)

<img width="268" height="69" alt="image" src="https://github.com/user-attachments/assets/f6bf51bd-2e9e-45e5-b7be-6937d31d94f1" />

Atributo android:backgroundTint: Se cambió el color de fondo de los botones a un naranja y verde para diferenciar las acciones de "Agregar" y "Ver".

Atributo android:textColor: Se puso en negro para asegurar que el texto sea legible sobre el fondo de color.

Atributo android:textStyle: Se puso en negrita "Agregar" y de cursiva "Ver" 
