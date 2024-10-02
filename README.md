# SGE - Sistema de Gestión de Empatican

Este proyecto es una aplicación de escritorio desarrollada en Python utilizando la biblioteca Tkinter. El **SGE (Sistema de Gestión de Empatican)** está diseñado para la gestión integral de clientes, perros, sesiones, seminarios y pagos, proporcionando una interfaz gráfica intuitiva que facilita el manejo de la información.

## Características Principales

### Gestión de Clientes
- Crear, modificar y eliminar registros de clientes.
- Mostrar todos los datos básicos de un cliente, como su **nombre**, **teléfono**, **email** y **dirección**.
- Capacidad para buscar clientes mediante un campo de búsqueda.

### Gestión de Perros
- Asociar uno o más perros a un cliente.
- Permitir la visualización de detalles del perro, incluyendo su **nombre**, **raza**, **edad**, y una **foto** del perro.
- Los perros vinculados al cliente se muestran en un menú desplegable para seleccionar entre varios si es necesario.

### Gestión de Sesiones
- Visualizar y gestionar sesiones de entrenamiento para cada perro.
- Mostrar la duración de la sesión y su descripción.
- Cambiar entre sesiones vinculadas a un perro específico mediante un menú desplegable.

### Gestión de Seminarios
- Asociar seminarios a cada cliente.
- Ver los detalles del seminario, incluyendo la descripción y fecha.
- Cambiar entre seminarios asociados a un cliente mediante un menú desplegable.

### Gestión de Pagos
- Registrar y visualizar los pagos relacionados con un cliente.
- Mostrar la fecha, monto y método de pago.
- Cambiar entre los pagos realizados mediante un menú desplegable.

### Otras Características
- **Cargar y visualizar fotos** de los perros.
- **Desplegables interactivos** para seleccionar perros, sesiones, seminarios y pagos.
- Interfaz gráfica fácil de usar para la gestión de datos.

## Requisitos del Sistema
- Python 3.7 o superior
- Bibliotecas necesarias: `tkinter`, `PIL` (Pillow), y cualquier otra que tu código requiera.

## Instalación
1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu_usuario/SGE_Empatican.git
    ```

2. Instala las dependencias:
    ```bash
    pip install pillow
    ```

3. Ejecuta la aplicación:
    ```bash
    python main.py
    ```

## Uso
El sistema está pensado para facilitar la gestión de clientes y sus mascotas en un entorno de trabajo para entrenadores de perros o centros de adiestramiento. El menú principal permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre clientes, perros, sesiones, seminarios y pagos.

## Autor
- Desarrollado por [Tu Nombre]

## Licencia
Este proyecto está bajo la licencia MIT.
