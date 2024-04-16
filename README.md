# APP WEB REACT + VITE

## Interfaz con API Externa:
La aplicación está configurada para interactuar con una API externa, manejando diversas operaciones HTTP como POST, GET, UPDATE, DELETE y configuraciones de HEADER.

### Funcionalidades
#### Logueo de Usuarios:
- Autenticación basada en credenciales (usuario y contraseña).
- Soporte para diferentes roles y privilegios que condicionan el acceso y funcionalidades dentro de la aplicación.

#### Gestión de Productos:
- Acceso restringido a usuarios con permisos adecuados.
- Funciones habilitadas incluyen la visualización, creación, edición y eliminación de productos, según los privilegios del usuario.

#### Gestión de Usuarios:
- Solo usuarios autorizados pueden acceder a esta funcionalidad.
- Permite crear, modificar, y eliminar usuarios, además de asignar roles y privilegios.

#### Vista del Cliente:
- Accesible únicamente por usuarios con el rol de cliente.
- Muestra información y funcionalidades pertinentes exclusivamente a clientes.

#### Vista de Restablecimiento de Clave:
- Disponible cuando un usuario autorizado restablece la clave de otro usuario o al crear un nuevo usuario.
- Esta vista se muestra después del logueo utilizando la nueva clave proporcionada.

### Validaciones

#### Control de Acceso:
- Los usuarios deben estar autenticados para acceder a cualquier ruta o vista de la aplicación. De no estarlo, serán redirigidos a la vista de login.

#### Restricciones basadas en Roles:
- Los accesos a diferentes vistas y funcionalidades están basados en los roles de los usuarios, asegurando que cada usuario solo acceda a lo que está autorizado.

#### Privilegios Específicos:
- Dependiendo de los privilegios configurados (como ver, insertar, actualizar, o eliminar datos), las acciones estarán disponibles o bloqueadas para el usuario.

#### Manejo de Expiración de Token:
- Al expirar el token de autenticación, se muestra una alerta al usuario para informarle de la situación. La aplicación deberá gestionar la renovación o requerir un nuevo inicio de sesión según sea necesario.

## Tecnologías Utilizadas en la Aplicación
- React + Vite - Para la construcción y desarrollo rápido de la interfaz de usuario.
- Bootstrap 5 - Framework CSS para diseño responsivo y estilización de la aplicación.
- Bootstrap Icons - Conjunto de íconos optimizados para Bootstrap, para mejorar la interfaz gráfica.
- SweetAlert2 - Biblioteca JavaScript para mostrar alertas personalizadas más atractivas y funcionales que los cuadros de diálogo estándar.

## Uso
<p>Para utilizar la aplicación, puedes acceder a la siguiente URL: Aplicación Web React </p>

#### Credenciales de Usuario:
**Rol**: Administrador <br/>
**Usuario**: emerson <br/>
**Contraseña**: 1234 <br/>
- Como administrador, tienes acceso completo para administrar todo el sistema.
<br/>

**Rol**: Supervisor <br/>
**Usuario**: jose <br/>
**Contraseña**: 1234 <br/>
- Como supervisor, puedes gestionar los productos en la aplicación.
<br/>

**Rol**: Cliente <br/>
**Usuario**: pedro <br/>
**Contraseña**: 1234 <br/>
- Como cliente, tienes acceso solo a la vista del catálogo de productos.

<br/>
**Rol**: Vendedor <br/>
**Usuario**: carlos <br/>
**Contraseña**: 1234 <br/>
- Como vendedor, puedes gestionar los productos en la aplicación.

### Funcionalidades por Rol:
 **Administrador:**   Acceso completo para administrar usuarios, productos y otras configuraciones del sistema.

**Supervisor:** Puede gestionar productos: crear, editar y eliminar productos.

**Cliente:** Acceso limitado a la vista del catálogo de productos.

**Vendedor:**Puede gestionar productos: crear, editar y eliminar productos.

### Instrucciones de Uso
Visita Aplicación Web React en tu navegador.

Ingresa con las credenciales correspondientes al rol que deseas probar (administrador, supervisor, cliente o vendedor).

Explora las funcionalidades disponibles según tu rol.

>Notas Importantes:
Asegúrate de utilizar las credenciales correctas según el rol que deseas probar.
Si tienes problemas de acceso o dudas, comunícate con el administrador del sistema.
