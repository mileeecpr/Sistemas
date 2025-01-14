
# Proyecto de Gestión de Inventarios y Citas

Este proyecto consiste en una aplicación para gestionar inventarios y citas, utilizando interfaces gráficas diseñadas con Qt y un cuaderno de Jupyter para ejecutar código Python. Además, incluye un archivo SQL para la gestión de la base de datos.

## Contenido del Proyecto

- **Archivos `.ui`**: Archivos de interfaz de usuario diseñados con Qt Designer para la gestión de inventarios y citas.
  - `agregar_inv.ui`: Formulario para agregar nuevos elementos al inventario.
  - `eliminar_inv.ui`: Formulario para eliminar elementos del inventario.
  - `modificar_inv.ui`: Formulario para modificar información de los elementos.
  - `nueva_cita.ui`: Formulario para agregar una nueva cita.
  - Otros archivos `.ui` para diversas funcionalidades.

- **`Proyecto.ipynb`**: Cuaderno de Jupyter que contiene el código Python para interactuar con la base de datos y posiblemente otros procesos relacionados con la gestión del inventario y la gestión de las citas

- **`proyecto.sql`**: Archivo SQL que define la estructura de la base de datos o contiene instrucciones para manipular los datos, además a partir de esto se puede establecer la entidad-reación.

## Requisitos

Para ejecutar este proyecto, asegúrate de tener instalados los siguientes requisitos:

- Python 3.8 o superior
- Qt Designer o PyQt5 para trabajar con archivos `.ui`
- Jupyter Notebook para ejecutar el archivo `.ipynb`
- Base de datos compatible con el archivo `proyecto.sql` (como MySQL o SQLite)

## Instalación

1. C este repositorio o descarga los archivos directamente.
2. Instala las dependencias y bibliotecas necesarias para Python.
   ```bash
   pip install PyQt5 jupyter
   ```
3. Abre el cuaderno de Jupyter para ejecutar el código Python.
   ```bash
   jupyter notebook Proyecto.ipynb
   ```
4. Importa la base de datos utilizando el archivo `proyecto.sql` en tu gestor de bases de datos.

## Uso

1. Abre y ejecuta el cuaderno `Proyecto.ipynb` para iniciar la interacción con la base de datos.
2. Utiliza los archivos `.ui` con Qt Designer para modificar o personalizar las interfaces.
3. Asegúrate de que la base de datos esté configurada correctamente antes de ejecutar los scripts.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para más información, puedes contactarme en:

- **Autores**: [Amanda Canales, Milena Pinochet, María Fernanda Ramírez y Anaís Salas]
- **Correos**: amanda.canales@usm.cl, milena.pinochet@usm.cl, maria.ramirezb@usm.cl y anais.salas@usm.cl
