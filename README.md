# PFinal-WebUCA2015
Proyecto Final de Especialización en Desarrollo Web  UCA 2015 
Descripción del Caso: Sistema de control de Documento para el Archivo
Nacional
El Archivo Nacional requiere de un sistema que permita el registro de los documentos/materiales
que son solicitados con diferentes fines. 
1. Depósito: Todos los documentos/materiales se encuentran en el depósito, por lo que para
realizar cualquier tipo de solicitud, se debe recurrir a este sitio. Cuando se da una salida de
documento desde el depósito, se registra la siguiente información: i) usuario responsable del
depósito; ii) hora de salida; iii) usuario que solicita (puede ser para cualquiera de los 5 posibles
destinos); iv) documento (sección1, volumen2, número3)4. 
1.1. Lectura: corresponde a la sala en donde los investigadores realizan consultas sobre los
documentos. Cuando un investigador está interesado en realizar una consulta, solicita al
encargado de lectura (quien luego pedirá a Depósito). Para entregar el documento, el
encargado de lectura registrará los siguientes datos: i) Investigador (Nombre, Apellido,
CI/Pasaporte, nacionalidad); ii) Documento a ser entregado (sección, volumen, número); iii)
Fecha/Hora de la entrega y de la devolución (que debe realizarse en el mismo día); iv) si
se solicita el material impreso o sólo en formato digital
1.2. Descripción: Se entregan los documentos para ser analizados y esto puede durar varios
días o semanas. Datos a ser registrados: i) usuario que hace entrega; ii) usuario que
recibe; iii) fecha/hora de entrega y devolución.
1.3. Conservación: Se entregan los documentos para ser analizados y esto puede durar varios
días o semanas. Datos a ser registrados: i) usuario que hace entrega; ii) usuario que
recibe; iii) fecha/hora de entrega y devolución. 
1.4. Exposición: se pueden entregar documentos que serán llevados a exposiciones fuera de
la institución. Para esto, se registra lo siguiente: i) usuario que hace entrega; ii) usuario que
recibe; iii) fecha/hora de entrega y devolución; iv) datos de la exposición (fecha inicio/fin,
lugar, motivo
1.5. Visita Guiada: Se podrá solicitar un material para realizar visita guiada dentro del predio,
para lo cual será necesario registrar la siguiente información: i) Responsable (Nombre,
Apellido, CI/Pasaporte, nacionalidad); ii) Documento a ser entregado (sección, volumen,
número); iii) Fecha/Hora de la entrega y de la devolución (que debe realizarse en el mismo
día); iv) Institución; v) Cantidad de alumnos
Para todos los casos, se debe registrar el usuario que entrega el documento y también el que
recibe. Se manejará un solo tipo de usuario de sistema, con privilegios para realizar registros.
Como los movimientos de documentos también son registrados en un libro de registro, cada vez
que se realice un ingreso, se deberá incluir los siguientes datos: registro (numérico), año, página.
El sistema deberá contar con la posibilidad de generar un reporte mensual con la siguiente
información: número de consultas realizadas en el periodo, número de materiales consultados,
número de visitas guiadas realizadas, documentos digitalizados solicitados. 
