# ACTIVIDADES
A continuación se detalla la documentación de las actividades de Android Studio.

## Actividad 1:
Instalar el entorno de programación y recorrer cada uno de los recursos. 
Crear un recurso de imagen.

1. Entorno de programación creado: 

![](/Users/josemorillo/Documents/PROYECTOS/Actividades/readmeImages/entorno.png)

2. Creación de recurso de imagen:
Se ha añadido una imagen de fondo en la vista main de nuestra app.

`   <ImageView
   android:id="@+id/iv_background_main"
   android:layout_width="0dp"
   android:layout_height="0dp"
   android:contentDescription="@string/iv_main_background"
   app:layout_constraintBottom_toBottomOf="parent"
   app:layout_constraintEnd_toEndOf="parent"
   app:layout_constraintHorizontal_bias="1.0"
   app:layout_constraintStart_toStartOf="parent"
   app:layout_constraintTop_toTopOf="parent"
   app:layout_constraintVertical_bias="0.0"
   app:srcCompat="@drawable/iv_main_background" />`

