# FleteAR

FleteAR es una aplicación web diseñada para vincular personas que necesitan servicios de flete con fleteros que desean ofrecer sus servicios. La aplicación permite a los fleteros registrar sus datos y vehículos, mientras que los usuarios pueden seleccionar el fletero que mejor se adapte a sus necesidades y calcular el costo aproximado del viaje.

## Tecnologías Utilizadas

- **Frontend**: HTML, CSS, Bootstrap, Tailwind CSS, JavaScript, jQuery, Mapbox
- **Backend**: PHP, SQL
- **Base de Datos**: MySQL (phpMyAdmin)
- **Servidor Local**: XAMPP
- **Autenticación y Sesiones**: PHP (con claves tokenizadas)
- **Pago**: API de MercadoPago, Transbank
- **Email**: PHPMailer

## Funcionalidades

### Para Fleteros

- **Registro y Login**: Los fleteros pueden registrarse y gestionar sus perfiles.
- **Registro de Vehículos**: Los fleteros pueden añadir información sobre sus vehículos, incluyendo capacidad de carga y tipo de vehículo.

### Para Usuarios

- **Registro y Login**: Los usuarios pueden registrarse y gestionar sus perfiles.
- **Selección de Fleteros**: Los usuarios pueden buscar y seleccionar fleteros basados en sus necesidades específicas.
- **Cálculo de Tarifas**: Los usuarios pueden calcular el costo aproximado del viaje ingresando los puntos de inicio y finalización en un mapa interactivo (Mapbox).

### General

- **Pago**: Integración con la API de MercadoPago para realizar pagos.
- **Correo Electrónico**: Envío de correos electrónicos mediante PHPMailer para confirmaciones y notificaciones.
- **Seguridad**: Gestión de sesiones y autenticación segura utilizando claves tokenizadas.

## Instalación y Configuración

2. **Configuración del Servidor**

   - Instalar [XAMPP](https://www.apachefriends.org/index.html).
   - Colocar el proyecto en la carpeta `htdocs` de XAMPP.

3. **Base de Datos**

   - Importar la base de datos `fletear.sql` ubicada en la carpeta `database` a través de phpMyAdmin.

4. **Configuración de MercadoPago**

   - Obtener las credenciales de la API de MercadoPago y configurarlas en el archivo `config.php`.

5. **Configuración de PHPMailer**

   - Configurar los parámetros de correo en el archivo `mail_config.php`.

6. **Iniciar el Servidor**

   - Iniciar Apache y MySQL desde el panel de control de XAMPP.

## Uso

- **Registro**: Tanto los fleteros como los usuarios deben registrarse para usar la aplicación.
- **Buscar Fletero**: Los usuarios pueden buscar fleteros disponibles ingresando los detalles del viaje.
- **Calcular Tarifa**: Utilizando el mapa interactivo, los usuarios pueden calcular la tarifa del servicio.
- **Pago**: Realizar el pago a través de la plataforma MercadoPago.
- **Confirmación**: Los usuarios reciben un correo de confirmación una vez que se ha realizado el pago.

## Capturas de Pantalla

![Página de Inicio](screenshots/home.png)
![Registro de Usuario](screenshots/register_user.png)
![Registro de Fletero](screenshots/register_fletero.png)
![Buscar Fletero](screenshots/search_fletero.png)
![Calcular Tarifa](screenshots/calculate_tariff.png)
![Pago](screenshots/payment.png)

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para discutir cualquier cambio que te gustaría hacer.


## Autor

**Agüero Esteban**

- **Estudiante de Ingeniería en Informática** en Universidad Santo Tomás de Aquino, Tucumán, Argentina.
- **Contacto**: [cuentauniversidad@gmail.com]
