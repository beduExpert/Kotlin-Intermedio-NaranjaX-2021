[`Kotlin Intermedio`](../../Readme.md) > [`Sesión 04`](../Readme.md) > `Reto 2`

## Ejemplo 2: Estructura del proyecto

<div style="text-align: justify;">


### 1. Objetivos :dart:

* Agregar navegación por acciones a un proyecto Android determinado.

### 2. Requisitos :clipboard:

1. Android Studio Instalado en nuestra computadora.

### 3. Desarrollo :computer:

El sistema de navegación también te permite navegar a través de las acciones. Como se mencionó anteriormente, las líneas que se muestran en el gráfico de navegación son representaciones visuales de las acciones.

En este reto es necesario agregar al proyecto una acción entre **home_dest** y **flow_step_one_dest**. Esta debe enviar del **home** al paso uno, por medio del botón Navigate **with action**.

A continuación se indican algunos puntos a considerar en la tarea.

- Es posible conectar dos pantallas desde **el gráfico de navegación** arrastrando de una pantalla a otra.
- En el ejemplo tres agregamos el evento del botón **Navigate to destination**, y en este reto puedes utilizar un evento similar, pero en este caso llamaría a la acción por su **id**.

</br>

<details>
    <summary>Solución</summary>

  mobile_navigation.xml -> dentro del home_dest

  ```xml
  <action
    android:id="@+id/next_action"
    app:destination="@+id/flow_step_one_dest"
    app:enterAnim="@anim/slide_in_right"
    app:exitAnim="@anim/slide_out_left"
    app:popEnterAnim="@anim/slide_in_left"
    app:popExitAnim="@anim/slide_out_right" />
  ```

  HomeFragment

  ```Kotlin
  view.findViewById<Button>(R.id.navigate_action_button)?.setOnClickListener {
      findNavController().navigate(R.id.next_action, null, options)
  }
  ```

</details>

</br>
</br>

[`Anterior`](../Reto-01/Readme.md) | [`Siguiente`](../Ejemplo-04/Readme.md)
