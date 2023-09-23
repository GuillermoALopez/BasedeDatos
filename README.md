

Manual de Usuario - TechsBlox-español
1. Inicio de Sesión

    Ejecuta el programa desde NetBeans.
   
    Se abrirá una pantalla de inicio de sesión.
         
    Ingresa tu nombre de usuario y contraseña.
   
    Haz clic en el botón "Ingresar". 

   ![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/06f96c8a-6efc-4530-98b5-9f3e2b8dffa9)



   

3. Interfaz Principal - TechsBlox
   
2.1 Ingreso de Datos

 Ingresa el código del producto en el campo "Código".
 
Escribe el nombre del producto en el campo "Nombre".

Introduce la cantidad de unidades en el campo "Unidades".

Especifica el precio unitario en el campo "Precio Unitario".

Selecciona la fecha de ingreso utilizando el calendari


![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/2c53a6ea-ba6a-4c6b-b5bc-ae0f1929bbce)



2.2 Botones de Acción

 Agregar: Guarda los datos ingresados en la base de datos.
 
 ![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/ca4bc6e3-fdb3-45f5-87b4-15c4674a77ee)


 Borrar: Permite eliminar un producto seleccionado de la base de datos.

 ![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/015baee5-416a-4be4-b239-3ee5063acc6c)

 
Modificar: Permite realizar cambios en la información de un producto existente.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/9b529f75-680f-44df-a3a2-4a9799160094)


Generar Reporte PDF: Abre un informe en formato PDF con los datos ingresados.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/61708837-e688-4d7b-a126-6b7e42f18ff8)


Buscar: Permite buscar productos por código o nombre.

Reiniciar: Limpia todos los campos.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/737ad9a6-9853-4443-8604-dbd4a1b9b235)


Cerrar Programa: Cierra la aplicación.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/fa2a64f9-769a-4dab-9a4b-bff9b095b07d)


2.3 Base de Datos de Productos

En esta sección se muestran todos los productos ingresados, incluyendo código, nombre, unidades, precio unitario y fecha de ingreso.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/57cf126c-88db-48e2-b279-687697e079bf)


3. Cierre del Programa

    Para cerrar la aplicación, haz clic en el botón "Cerrar Programa" ubicado en la interfaz principal.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/fa2a64f9-769a-4dab-9a4b-bff9b095b07d)



   User Manual - TechsBlox-ingles 
1. Login

    Run the program from NetBeans.
   
   A login screen will appear.

    Enter your username and password.

    Click the "Login" button.

 ![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/06f96c8a-6efc-4530-98b5-9f3e2b8dffa9)

3. Main Interface - TechsBlox
2.1 Data Entry

  Enter the product code in the "Code" field.
   
Type the product name in the "Name" field.

Input the quantity in the "Units" field.

Specify the unit price in the "Unit Price" field.

Select the entry date using the calendar.

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/2c53a6ea-ba6a-4c6b-b5bc-ae0f1929bbce)

2.2 Action Buttons

Add: Saves the entered data in the database. 
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/ca4bc6e3-fdb3-45f5-87b4-15c4674a77ee)

Delete: Allows you to remove a selected product from the database.
 ![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/015baee5-416a-4be4-b239-3ee5063acc6c)

Modify: Enables changes to the information of an existing product.
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/9b529f75-680f-44df-a3a2-4a9799160094)
   
Generate PDF Report: Opens a report in PDF format with the entered data.
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/61708837-e688-4d7b-a126-6b7e42f18ff8)
    
Search: Allows you to search for products by code or name.
    
Reset: Clears all fields.
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/737ad9a6-9853-4443-8604-dbd4a1b9b235)
    
Close Program: Closes the application.
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/fa2a64f9-769a-4dab-9a4b-bff9b095b07d)

2.3 Product Database

In this section, all entered products are displayed, including code, name, units, unit price, and entry date.
![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/57cf126c-88db-48e2-b279-687697e079bf)

3. Closing the Program

To close the application, click the "Close Program" button located on the main interface

![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/fa2a64f9-769a-4dab-9a4b-bff9b095b07d)


Manual Técnico: Conexión a la Base de Datos
Introducción

El objetivo de este manual es proporcionar una descripción detallada de la clase Conexion que se encarga de establecer la conexión con la base de datos en el sistema de gestión de productos.
Estructura del Código

La clase Conexion está contenida en el paquete basededatos y se encarga de gestionar la conexión con la base de datos MySQL.
Clase Conexion
Descripción

Esta clase se encarga de establecer la conexión con la base de datos y proporciona un método para obtener la instancia de la conexión.
Atributos

 con: Objeto de tipo Connection que representa la conexión a la base de datos.

Métodos

 public Conexion(): Constructor de la clase. Se encarga de cargar el controlador de MySQL y establecer la conexión con la base de datos utilizando la URL de conexión, nombre de usuario y contraseña.

public Connection getConnection(): Método que devuelve la instancia de la conexión a la base de datos. Permite a otras clases obtener acceso a la conexión.

Connection getConexion(): Este método no está implementado y lanza una excepción de tipo UnsupportedOperationException si se invoca. Puede ser un remanente de código no utilizado.

Configuración de la Conexión

La conexión se establece utilizando la siguiente información:

 Controlador JDBC: com.mysql.jdbc.Driver
    URL de Conexión: jdbc:mysql://localhost:3306/bdnegocio
    Usuario: root
    Contraseña: (En este caso, está en blanco, pero en una configuración real debería tener una contraseña segura).

Gestión de Errores

En caso de que ocurra un error al establecer la conexión, se captura una excepción y se imprime un mensaje de error en la consola.
Consideraciones

Asegúrese de tener el controlador MySQL JDBC en el classpath del proyecto.

Asegúrese de que el servidor MySQL esté en ejecución y escuchando en el puerto 3306.

Cambie el nombre de usuario y la contraseña según sea necesario para su configuración de MySQL.




Manual Técnico: Sistema de Inicio de Sesión
Introducción

El sistema de inicio de sesión proporciona a los usuarios una interfaz para ingresar a la aplicación. Este manual detalla la implementación del código Java que maneja la autenticación de usuarios.
Estructura del Código

La clase Usuario es una ventana de interfaz gráfica de usuario (GUI) que proporciona campos para ingresar el nombre de usuario y la contraseña. Luego, verifica las credenciales ingresadas y permite el acceso si son correctas.
Clase Usuario
Descripción

Esta clase representa la ventana de inicio de sesión de la aplicación. Permite a los usuarios ingresar sus credenciales para acceder a la funcionalidad principal.
Componentes de la Interfaz

jLabel2: Etiqueta de texto que indica "Bienvenido Usuario".
    jLabel3: Etiqueta de texto que indica "Usuario".
    jLabel4: Etiqueta de texto que indica "Contraseña".
    txtusuario: Campo de texto para ingresar el nombre de usuario.
    password: Campo de contraseña para ingresar la contraseña.
    jButton1: Botón "Ingresar" que inicia el proceso de autenticación.

Métodos

private void jButton1MouseClicked(java.awt.event.MouseEvent evt): Método invocado cuando se hace clic en el botón "Ingresar". Verifica las credenciales ingresadas y, si son correctas, abre la ventana principal de la aplicación bdnegocio. Si no, muestra un mensaje de error.

public static void main(String args[]): El método principal que inicia la aplicación. Crea una instancia de la clase Usuario y la hace visible.

Configuración de Credenciales

Las credenciales de usuario (nombre de usuario y contraseña) están codificadas directamente en el método jButton1MouseClicked. En un entorno real, se deben verificar las credenciales contra una base de datos o un sistema de autenticación externo.
Consideraciones

Seguridad de las Credenciales: En una aplicación real, no es seguro codificar las credenciales en el código fuente. Se deben almacenar de forma segura y utilizar métodos de autenticación robustos.

Manejo de Errores: En una implementación real, se debe manejar de manera adecuada el flujo de errores, incluidos los casos de credenciales incorrectas y posibles errores de conexión.

Pruebas: Se recomienda realizar pruebas exhaustivas del sistema de inicio de sesión para garantizar su funcionalidad y seguridad.




Manual Técnico: Sistema de Gestión de Productos
Introducción

El sistema de gestión de productos es una aplicación de escritorio diseñada para administrar información sobre productos, incluyendo su código, nombre, precio unitario, cantidad de unidades y fecha de ingreso. Este manual técnico proporciona una descripción detallada del código fuente proporcionado.
Estructura del Código

El código fuente está escrito en Java y utiliza el entorno de desarrollo NetBeans. El proyecto está organizado en un paquete llamado basededatos, que contiene una serie de clases y recursos necesarios para el funcionamiento del sistema.
Clases Principales
Clase bdnegocio

Esta clase es la interfaz principal de la aplicación y contiene los elementos gráficos (ventanas, botones, campos de texto, etc.) y la lógica para interactuar con la base de datos.
Atributos

 con1: Objeto de la clase Conexion utilizado para establecer la conexión con la base de datos.
    conet: Objeto de tipo Connection que representa la conexión a la base de datos.
    modelo: Objeto de tipo DefaultTableModel utilizado para manejar los datos de la tabla.
    st: Objeto de tipo Statement para ejecutar consultas SQL.
    rs: Objeto de tipo ResultSet que almacena el resultado de las consultas SQL.
    idc: Variable entera utilizada para almacenar el ID del producto.

Métodos Principales

public bdnegocio(): Constructor de la clase. Se encarga de inicializar los componentes de la interfaz gráfica y establecer la conexión con la base de datos.

   private void initComponents(): Método generado automáticamente por el entorno de desarrollo que inicializa y configura todos los componentes visuales.

private void jButton1ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Agregar". Se encarga de agregar un nuevo producto a la base de datos.

private void jButton3ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Eliminar". Elimina un producto de la base de datos.

private void jButton2ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Modificar". Permite modificar los datos de un producto existente.

private void jButton4ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Salir". Cierra la aplicación.

 private void jButton5ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Generar Reporte". Genera y muestra un informe con los productos.

private void jToggleButton1ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón de búsqueda. Realiza una búsqueda de productos por código o nombre.

private void jButton6ActionPerformed(java.awt.event.ActionEvent evt): Método que se ejecuta cuando se presiona el botón "Consultar". Consulta y actualiza la tabla de productos.

void consultar(): Método que consulta la base de datos y actualiza la tabla de productos.






![imagen](https://github.com/GuillermoALopez/BasedeDatos/assets/145726629/a4e53256-00cf-4c80-8e4a-83c96e0d21a3)




