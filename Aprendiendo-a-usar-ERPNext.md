# Aprendiendo a usar ERPNext

## Modulo 1

### 1.0 Introducción
Este documento asume que usted tiene curiosidad de saber de qué se trata ERPNext y que está interesado en aprender como usarlo.

### 1.1 Resumen
ERPNext es un software que corre en una máquina con sistema operativo linux (en Virtualbox
 se puede correr en cualquier sistema oeprativo) o en un servidor. Lo puedes acceder con un navegador
 web. En este software ingresas registros sobre muchas cosas relacionadas a tu empresa u organización.

* Clientes
* Proveedores
* Ventas
* Contabilidad
* Inventario de Productos (Stock)
* Proyectos
* Manufactura
* Ventas al detalle

También incorpora ciertas funciones especificas del dominio de ciertas industrias o actividades

* Educacion
* Agricultura
* Salud
* Organizaciones sin Fines de Lucro

ERPNext cuenta con documentación básica, videos y un grupo de soporte que le puede apoyar mientras esta guía es completada.

ERPNext también tiene una parte que le permite a tus clientes y proveedores acceder a un portal para
 gestionar información relacionada con tu empresa, asi como un sitio web para comercio electrónico.
 
* Portal clientes y proveedores
* Sitio Web
* Comercio electronico (e-commerce)

### 1.2 Estructura
The following course or tutorial is divided into 5 modules, which will enable you to master ERPNext.

>* Modulo 1: Introduction a ERPNext
>* Modulo 2: Uso básico
>* Modulo 3: Uso intermedio
>* Modulo 4: Uso avanzado
>* Modulo 5: Convirtiéndose en experto

Este curso está dividido en 5 modulos. Cada módulo llevará el aprendizaje de lo más general 
a lo más específico, de la misma manera que hablamos de un barco en términos generales, 
cada módulo adicional irá explorando témas más específicos sobre el barco, como sistemas 
de propulsión, achique, navegación, tripulación, etc.  Hasta finalmente llegar al detalle
 de los componentes individuales como motores, bombas, brújula, funciones del capitán, etc.
Con esto, pueden ahondar cuanto sea necesario aprender a utilizar ERPNext.

A mi me gusta llevar un órden específico para poder mejor referirme a algún tema, por lo 
tanto lo he estructurado con numeración por niveles, separado por decimales. Cada módulo 
es el nivel 1, llevando solamente un numero entero. El nivel 2 lo representa el conjunto 
del numero de nivel uno, separado por un punto, y luego otro numero que inicia la cuenta 
ordinal del tema dentro del modulo.
Ustedes podrán referirse rápidamente a un tema específico por la numeración.
Cada sub-tema se separa por un punto decimal del numero que representa el tema padre, o principal.

### 1.3 Objetivos del Módulo 1
- Como acceder o instalar y configurar ERPNext
El usuario utiliza cualquier navegador web para poder gestionar todo lo relacionado con el sistema.

Esto puede correr localmente en una máquina Linux, o en un servidor virtual en cualquier 
sistema operativo.

Idealmente, puede correr en un servidor con una direccion de IP pública, para poder acceder
 al servicio desde cualquier dispositivo o lugar. (Ordenador, Smartphone, Tablet)

Este modulo se enfoca en aprender a instalarlo, configurarlo y usar esta instancia ya 
instalada de ERPNext, para satisfacer las necesidades de contabilidad y administración de una empresa.

### 1.4 Obtenga una Instancia de ERPNext

#### 1.4.1 Cuenta de prueba en erpnext.com
La forma más rápida y facil es aperturando una cuenta en [erpnext.com](https://www.erpnext.com)
Media vez haya completado la configuración de este método, vaya al Módulo 2
#### 1.4.2 - Instalación local en cualquier sistema operativo - VirtualBox
La segunda forma más fácil es descargando una imagen virtual pre-instalada para usar con VirtualBox.
Descargue VirtualBox desde [aquí](https://www.virtualbox.org/)
Siendo ERPNext un software de licencia 
[Licencia de código abierto](https://es.wikipedia.org/wiki/Licencia_de_c%C3%B3digo_abierto),
 se puede descargar directamente desde este sitio y utilizar para cualquier propósito permitido en la licencia:
[https://erpnext.com/download](https://erpnext.com/download)
Corre VirtualBox, importa la aplicación e inicia el servidor.
Asegurese de configurar las tarjetas virtuales de redes de la maquina virtual adecuadamente.
Yo utilizo una conexion de puente a mi conexión WiFi existente en una MAC, para que obtenga una IP
de mi router. De esta manera, puedo acceder con una dirección local mediante mi navegador.

## Módulo 2: Uso Básico

En este módulo conoceremos como operar el programa, como configurar lo más básico e importante,
 como encontrar ayuda a preguntas específicas y exploraremos el concepto de los 
 Tipos de Documentos o DocTypes. El resto del modulo será la exploratoria inicial de los 
 módulos del programa para
 
 * Contabilidad
 * Recursos Humanos
 * Almacén o Inventario
 * Compras
 * Ventas
 * CRM (Gestión de Clientes)
 * Manufactura
 * Proyectos
 * Bienes (Activos)
 * Sitio Web

### 2.0 Objetivos del Módulo 2

- Operacion básica del marco Frappé/ ERPNext
- Configurar ERPNext para el manejo de productos y servicios para la compra o venta
- Configurar las cuentas contables, y categorias de productos y servicios
- Administrar proveedores y clientes
- Hacer un ciclo de compra (Desde cotizar, hasta Pagar)
- Hacer un ciclo de venta (Desde obtener una iniciativa, hasta recibir el pago del cliente)
- Administrar inventarios

### 2.1 Operación Básica
#### 2.1.1 Como Hacer login ([Video 002](https://youtu.be/Znj-Fy_BRwA))
1. Abra su navegador web
2. Coloca la dirección IP o dominio de ERPNext en la barra de direcciones de su navegador
3. Cuando cargue la página de acceso a ERPNext, si no hay dos campos par aingresar usuario y contraseña,
	presione el enlace de arriba a la derecha para elegir el objeto del menu que dice: "Ir a Escritorio"
4. Ingrese su usuario
5. Ingrese su contraseña
6. Presiona **Sign In** o **Acceder**
7. Listo, se debe mostrar el escritorio

#### 2.1.2 Configure su usuario ([Video 003](https://youtu.be/tdKe0_IM1DA))
##### 2.1.2.1 - Cambie su contraseña
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Mi Configuracion** o **My Settings**
3. En la página que surge, desplácese hacia abajo en la ventana y en la sección de
	**Cambiar Contraseña** haga clic para desplegar y mostrar el campo donde puede ingresar una nueva contraseña
4. Ingrese contraseña nueva
5. Seleccione o no las opciones de:
	5.1 Enviar notificacion de cambio de contraseña
	5.2 Salga de todos los dispositivos mientras cambia la contraseña
6. Desplácese hacia arriba y haga clic en **Guardar**

##### 2.1.2.2 - Cambie su idioma
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Mi Configuracion** o **My Settings**
3. En el campo de *Idioma* o *Language*, desplácese para seleccionar
4. Seleccione uno haciendo clic sobre él o escribiéndolo.
6. Desplácese hacia arriba y haga clic en **Guardar**

##### 2.1.2.3 - Agregue mas informacion
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Mi Configuracion** o **My Settings**
3. Desplácese hacia abajo y haga click en el desplegable de **Más Información**
4. Agregue un genero
5. Agregue un telefono
6. Agregue un movil
7. Agregue una fecha de nacimiento
8. Agregue una Ubicacion
9. Agregue una corta biografia
10. Seleccione "*Sonidos Silenciados*" si no desea ecuchar los sonidos de confirmación de ERPNext
11. Desplácese hacia arriba y haga clic en **Guardar**

##### 2.1.2.4 - Agregue una imagen al fondo de su escritorio
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Mi Configuracion** o **My Settings**
3. Desplácese hacia abajo y haga click en el desplegable de **Fondo de escritorio**
	 y haga clic para desplegar.
4. Haga Clic en **Adjuntar**
5. Seleccione un archivo de dimensiones deseadas y haga click en **Subir**
6. Revise el Estilo de fondo, dejandolo pantalla completa
7. Modifique la imagen, el estilo de fondo hasta estar satisfecho con su imagen de fondo.

##### 2.1.2.5 - Retire la imagen de fondo de escritorio
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Mi Configuracion** o **My Settings**
3. Desplácese hacia abajo y haga click en el desplegable de **Fondo de escritorio**
	 y haga clic para desplegar.
4. Haga Clic en la x al lado del nombre del archivo ya adjunto para eliminar el fondo de
	escritorio.

##### 2.1.2.6 - Configure iconos del escritorio de trabajo ([Video 004](https://youtu.be/ZJu6lH4DGh4))
1. Desde el escritorio, haga clic arriba a la derecha en la imagen de su usuario
	para mostrar un menú desplegable.
2. Haga clic en **Establecer Iconos de escritorio** o **Set Desktop Icons**
3. Puede elegir cambiar **Por Usuario** y su usuario, o puede elegir a todos
4. Puede tambien **Seleccionar todos** y luego hacer clic para desmarcar.
5. Seleccione los módulos que desea que se muestren en el escritorio
6. Desplácese hacia arriba y haga clic en **Guardar**

> Para mover los iconos, haga clic y detener hasta que los iconos se sacudan
	Luego mueva el icono al lugar deseado
	Al terminar haga clic en el escritorio para que se queden quietos
> Para eliminarlos siga el mismo procedimiento indicado arriba, solo que haga clic en la x para borrarlos

##### 2.1.2.1 Agregue usuario (Video 005)
#### 2.1.3 El marco de Frappé ([Video 006](https://youtu.be/DjkP1ie9D3k))
* Imagenes
* Archivos Adjuntos
* Asignaciones
* Etiquetas
* Usuarios
* Compartiendo
* Momento de creación y edición
* Comentarios
* Botones de acción específicos por tipo de documento
* El botón de **Hacer** (Make)
* Duplicacion de documentos
	Considero esta característica particular de ERPNext una de las más útiles para transacciones
	diarias, porque permite copiar datos desde un tipo de documento existente como una orden de compra
	y crear una nueva con los mismos productos, solo para cambiar montos y fechas o cualquier otro
	parametro para ajustarse a esa nueva instancia particular del documento nuevo.
	
##### 2.1.3.1 Doctypes o tipos de documentos. Principales y de apoyo (Video 007)
Example: Un tipo de documento principal es uno como Artículo o Factura de Venta. Un tipo de documento
de apoyo es un Atributo de Articulo o un Articulo de Factura de Venta.

* Usuario
* Articulo
* Precio de Articulo
* Personalizando (Agregando campos a la medida)
* Secuencias y series

#### 2.1.4 Dónde encontrar soporte y ayuda (Video 008)
[Documentacion](https://erpnext.org/docs/user/manual)
[Canal de Videos YouTube (Inglés) - en](https://www.youtube.com/c/erpnext)
[Canal de Videos YouTube en Español - es](https://www.youtube.com/playlist?list=PLp25mpSQVMLcpSEVkQmuH0piDVeHIEIX8)
[Foro de discusión (Inglés) - en](https://discuss.erpnext.com/)
[Capítulos](https://erpnext.org/chapters)

### 2.2 Modulos del programa
#### 2.2.1 - Cuentas Contables
##### 2.2.1.1 - Compañía (Video 009)
##### 2.2.1.2 - Centros de costo (creando centros de costo) (Video 010)
##### 2.2.1.3 - Plan de cuentas o arbol de cuentas (creando cuentas) (Video 011)
##### 2.2.1.4 - Partida contable (Asiento contable) (Video 012)
##### 2.2.1.5 - Partida de Apertura (Video 013)
#### 2.2.2 - Recursos Humanos
##### 2.2.2.1 - Empleados (Video 014)

##### 2.2.2.2 - Sucursal (Video 015)
##### 2.2.2.3 - Departamento (Video 016)
##### 2.2.2.4 - Puesto (Video 017)
#### 2.2.3 - Almacén o Inventario
##### 2.2.3.1 - Grupos de productos (creando grupos) (Video 018)
##### 2.2.3.2 - Bodegas (Video 019)
##### 2.2.3.3 - Artículos o productos (Video 020)
	La importancia de la casilla de verificación "Mantener Stock" o no!
	El valor de la valuación es cargado cuando se valida un recibo de compra.
#### 2.2.4 - Compras
##### 2.2.4.1 - Agregar un proveedor (Video 021)
##### 2.2.4.2 - Modificar proveedores  (Video 022)
##### 2.2.4.3 - Ingresar cotizaciones de proveedores  (Video 023)
##### 2.2.4.4 - Ingresar una compra (Video 024)
##### 2.2.4.5 - Realizar una compra con cotización, orden de compra, recibo de compra, factura y pago  (Video 025)
#### 2.2.5 - Ventas
##### 2.2.5.1 - Agregar un cliente  (Video 026)
##### 2.2.5.2 - Modificar clientes  (Video 027)
##### 2.2.5.3 - Ingresar cotizaciones para clientes  (Video 028)
##### 2.2.5.4 - Realizar una venta  (Video 029)
##### 2.2.5.5 - Ciclo completo - Realizar una venta con cotización, orden de venta, nota de entrega, factura, cobro y pago  (Video 030)
#### 2.2.6 - CRM (Manejo de Recursos: Clientes)
##### 2.2.6.1 - Uso del modulo de CRM para incrementar las ventas y la atención al cliente  (Video 031)
##### 2.2.5.2 - Iniciativas y Oportunidades (Video 032)
##### 2.2.5.3 - Campañas (Video 033)
#### 2.2.7 - Manufactura
##### 2.2.7.1 - Listado de materiales (Video 034)
	Para manufactura o subcontratación
	Es esencial para crear un listado de materiales, tener un ingreso a almacen o bodega, o un recibo de compra, de todos y cada uno de los materiales a ser utilizados en el listado de materiales.
	Esto implica que los articulos o productos (items) ya deben de estar creados, así como un ingreso a bodega o un recibo de compra.
	Para el producto que se manufactura, solo debe existir el articulo o producto creado en bodega.
#### 2.2.8 - Proyectos
##### 2.2.8.1 - Proyecto interno con tareas y progreso (Video 035)
#### 2.2.9 - Bienes
##### 2.2.7.2 Categoria de Bienes o Activos (Video 036)
##### 2.2.7.1 Creando un Bien o Activo (Video 037)
#### 2.2.10 - Sitio Web
##### 2.2.10.1 - Creando una Pagina Web (Video 038)
##### 2.2.10.2 - Pasos para crear una pagina web - Basado en conferencia Octubre 2017
[Rushabh - Frappe Portal, Website + Web Forms + E-commerce](https://www.youtube.com/watch?v=ruJBetD7In0)
###### 1 - Prepare su sitio si no lo ha hecho
Lanze su sitio en un servidor remoto si no lo ha habilitado.

###### 2- Planifique su estructura
En este caso, el sitio ejemplo maneja eventos. 
Cada evento tiene una imagen, un titulo, una fecha y un boton para reservar.
Luego hay contenido sobre lo que el evento posee.

Se creara un modulo para eventos publicos en ERPNext.
Luego se creará un objeto llamado "Evento".
Para reservar un ticket, crearemos un objeto "Ticket"
Esto son dos DocTypes que crearemos.
Finalmente, crearemos una vista web.

Planifique su "tema" del sitio basado en sus colores.

###### 3 - Configuremos el Tema
Configuremos el "theme".
Hay un Standard theme, pero Hagamos uno nuevo.
**Sitio Web > Ajustes > Tema del Sitio**

1. Agregue el nombre del tema que desea
2. Asegurese que la caja de seleccion **Aplicar estilo** esté marcada. Esta si debe estar elegida para este ejemplo.
3. Si es un estilo personalizado, marque la caja de **Personalizado?**. Para este ejemplo, no la elija.
4. Elija si desea aplicar estilo de texto por medio de ERPNext marcando la caja de **Aplicar Estilos de Texto**.
	4.1 Al marcar la caja vera los campos para:
		4.1.1 Tamaño de la Fuente
		4.1.2 Fuente de Google (Texto)
		4.1.3 Fuente de Google (Encabezados)
		4.1.4 Color del Texto
		4.1.5 Color de los Enlaces
		4.1.6 Estilo del Encabezado
		4.1.7 Color de la Barra Superior
		4.1.8 Color del Texto de la Barra Superior
		4.1.9 Color del Pie de Página
		4.1.10 Color deL Texto del Pie de Página	
5. En la seccion de **Background**
	5.1 Elija el color que desea, usando el selector de colores o ingresando un valor HEX: "#FFFFFF"
	5.2 Puede elejir una imagen, la cual estará sobrepuesta.
6. En la seccion de estilo usando CSS, usted puede ingresar los elementos CSS personalizados, sustituyendo el paso 4
	6.1 Recomendaciones:
		6.1.1 Ajuste el color de la barra superior: `.navbar {background-color: #0075C9;}`
		6.1.2 Ajuste la alineacion vertical de los enlaces: `.nav > li {margin-top: 20px;}`  (Cambie los valores de 20 a otros...)
7. En la seccion de JavaScript, puede ingresar el JavaScript a la medida que usted desee para la página principal.
###### 4 - Configuremos Los Ajustes del Sitio Web
1. Navegue a **Sitio Web > Ajustes > Ajustes del Sitio web**
2. En la sección de **Landing Page**
	2.1 Indique en el campo de **Pagina Principal**, la página inicial que verá el usuario
		2.1.1 index
		2.1.2 login
		2.1.3 products
		2.1.4 blog
		2.1.5 about
		2.1.6 contact
	2.2 Indique el prefijo del titulo que aparecera en las ventanas o pestañas del navegador.
		2.2.1 - [Prefijo] - título de la página
3. En la sección de **Tema de Sitio**, seleccione el tema que acaba de crear anteriormente
	Esto activará el tema para poderlo ver en el sitio web. De lo contrario se mostrará el tema estándar.
4. En la sección de **Marca**, puede subir una imagen de su marca para mostrar arriba a la izquierda
	4.1 Alternativamente puede colocar tags de HTML para su sección de título en la **barra superior**
		> Esto le da flexibilidad para mostrar lo que desea, desde cambiar el estilo de los enlaces,
		> hasta mostrar elementos HTML de otro tipo. Sin embargo, los enlaces per se, y sus destinos,
		> es mejor permitir que los controle EPRNext.
5. En la seccion de **Barra Superior**, usted indica en una tabla el nombre del enlace y la ruta a la que enlaza en su pagina.
	5.1 También puede indicar si coloca una barra de **Busqueda** al lado de los enlaces.
6. En la sección de **Banner**, usted puede configurar lo que va *Arriba* de los enlaces, a lo que se llama la **Barra superior**
	6.1 Esto se hace mediante simple HTML, en donde puede referir imagenes, otros sitios, etc.
7. En la sección de **Pie de Página**, usted define a nombre de quien están los derechos de Autor, y Una sección de dirección
	7.1 La sección de dirección es un campo de Texto enriquecido pero puede optar por ingresar HTML haciendo clic en el ícono de "< / >". Usted puede agregar imágenes, configurar encabezados, etc.
	7.2 Hay una tabla donde puede colocar enlaces de una manera ordenada en el **Pie de página**. Haga clic en la flecha **▼** para ver los campos que faltan en la tabla.
		7.2.1 Etiqueta: Es el texto que aparecerá en la página
		7.2.2 Etiqueta Madre: En caso que desee colocar una etiqueta encajada bajo otra, puede indicar el nombre de la etiqueta madre acá.
		7.2.3 URL: El enlace a donde desea llevar al usuario, a este enlace se le antepondrá el nombre de su dominio. Es decir, el enlace solo lo llev aa páginas de su dominio.
		7.2.4 Objetivo: Aqui usted indica en que ventana abre el enlace. Deje en blanco si abre en la misma ventana.
			> Si desea que abra en una ventana nueva, escriba: **"_blank"**
		7.2.5 Derecha: Esta caja de selección indica si inicia desde la derecha hasta la izquierda el orden (para la barra superior) ????
	7.3 Esconder el enlace para subscripción del **boletín de noticias**. Esta caja de selección debe estar marcada si desea esconder la porción que le permite a los usuarios
	subscribirse a los boletines de su sitio web.
8. La seccion de **Integraciones** permite especificar datos para sitios como **Google.com** y su sistema de analíticos.
9. La sección de **Mas Información** le permite adjuntar un icono de favoritos y deshabilitar la opcion de inscripcion como usuario del sitio web
	9.1 El **favicon** es un icono a base de una imagen de 16x16 pixelas, utilizado para la sección de favoritos de su navegador.
		Este ícono también identifica su sitio al mostrar en las pestañas o titulos de su navegador.
10. La sección de encabezado de **HTML y robots** le permite agregar HTML que no será visible en la página, pero que le permite
	extender la funcionalidad de su página.  En el campo **HTML** coloque lo que va en sección < head > < / head >. En el campo de robots.txt
	coloque el texto que deberán procesar los robots de los motóres de búsqueda.
###### 4 - Creando una pagina principal nueva
1. Navegue a **Sitio Web > Sitio Web > Pagina Web**
2. En la sección de **Titulo** puede indicar el nombre de la página.
	2.1 En **Ruta** indique la ruta del URL que se le postpone a la direccion de su dominio configurado
	2.2 En **Presentación de Diapositivas** elija una configuración previamente realizada de **Diapositivas**.
	2.3 La caja de **Publicado** le permite habilitar o deshabilitar rápidamente la publicación de esa página.
	2.4 La caja de **Mostrar Titulo** muestra o esconde el título de la página web en la pestaña de la ventana ????
3. En la sección de contenido, coloque en el campo de **Seccion Principal** el texto que desee mostrar a sus usuarios cuando llegan a esta página.
4. En la sección de **Secuencia de Comandos**, puede ingresar una **Secuencia de Comandos** en lenguaje JavaScript.
5. En la sección de **Estilo**, puede seleccionar insertar un estilo específico en CSS, marcando la **caja** de **Insertar Estilo**
	5.1 Al marcar la caja de **Insertar Estilo** se habilitará un campo para seleccionar la alineación del Texto **Alinear Texto**
	5.2 También se habilita el campo de **CSS** para colocar los estilos según sea necesario.
6. En la sección de **Barra Lateral y Comentarios** puede marcar la caja para mostrar la barra lateral u ocultarla.
	6.1 En el campo de **Barra Lateral**, seleccione una Barra Lateral previamente configurada.
	6.2 También puede habilitar la opción de **Habilitar Comentarios**, e indicar la prioridad de carga.
7. La Seccion de **Encabezado y Descripción** le permite configurar tres cosas:
	7.1 La **Descripción** es para optimizar los motores de búsqueda. Solo texto.
	7.2 El **Encabezado** es para HTML, opcional.
	7.3 Las **Migas de pan** le permiten mantener el rastro de sus páginas ordenadamente.
		Muestran la ubicación relativo a la página principal. Debe ser indicado como:
		> [{"label":_trabajos,"route":"trabajos"}]





###### 5 - Configuración de la Barra Lateral

###### 6 - Configurando DocTypes para publicar su contenido en la web
Cualquier DocType que usted desee puede ser publicado en la página web.
Es necesario configurar developer mode para el sitio en `site_config.json`
Para hacer esto, debemos agregarle un switch que le permite ser visto en la web.

1. Usando el **DocType list** (se accede desde el **Awesome Bar** superior), abra el **DocType** deseado
2. Existe una sección hasta abajo que se llama **Web View**
3. Hay dos cajas de seleccion que permiten compartir en público.
	3.1 **Tiene Vista en la Web** es una caja que le permite habilitar este DocType para vista en la web.
		Esto solo funciona par ausuarios registrados en el portal.
	3.2 **Permitir Vista para Invitados** es una caja selectora que le permite a un usuario no registrado,
		ver este tipo de DocType.  Basicamente con esto usted publica este DocType en su dominio.
4. Luego, hay que indicar la ruta o el directorio en donde se podrán ver este DocType  (La ruta debe estar definida en **Website Settings > Top Bar > Fila con la ruta y nombre**) ???
5. Como un ultimo control detallado o específico, es importante que el DocType posea un campo que el usuario marca en cada *Instancia* del DocType individual
	que lo publica o no. Esto es util en caso sea necesario habilitar o deshabilitar elementos individuales.
	5.1 Nota importante:  Si es un nuevo DocType el que esta creando, obligatoriamente debe crear dos campos:
		5.1.1 Un campo con un nombre como *Published* de tipo **Check**
			para poderlo utilizar rápidamente para publicar ese nuevo DocType.
		5.1.2 Un campo con la **Ruta** o el folder relativo al nombre del dominio para accesar. P. Ej. */eventos*
			Si no hay ruta, es posible que elija el **Titulo** del DocType como ruta amigable de URL, pero es mejor especificarlo para evitar problemas y confusiones.
6. Finalmente hay dos cosas importantes que realizar:
	6.1 El campo de **Published** que uste desea utilizar (creado o configurado en paso 5), hay que enlazarlo con el campo de
	**Campo de Está Publicado**
	6.2 Definir la ruta (URL de la web, p. ej. *http://dominio.com/ruta_que_desea/*) en la que desea que aparezcan las
	instancias individuales de este DocType.
7. Guarde la configuración del DocType haciendo clic en **Guardar** o **CTRL/CMD + S**
8. Esto creará una carpeta con plantillas adentro de la carpeta del módulo y doctype especificado en **erpnext**, llamado igual que el DocType que acaba de crear o que desea mostrar.
	La ruta completa es esta (reemplace con el nombre del modulo y doctype que necesita): 
	> /home/frappe/frappe-bench/apps/erpnext/erpnext/[nombre_del_modulo]/doctype/[nombre_del_doctype]/templates/
	7.1 Adentro de esta carpeta habrán dos archivos HTML.
	* Una plantilla para cada DocType: (Esta muestra las características de cada elemento DocType individual)
	> [nombre_del_doctype].html
	* Una página para mostrar los DocTypes como listado (tarjetas, filas, etc.) Esta muestra todos los disponibles, y enlaza a las individuales.
	> [nombre_del_doctype]_row.html
###### 7 - Modificando Las Plantillas Archivos html
Cuando ya estén creadas las plantillas, se pueden modificar directamente para controlar detalladamente como se visualiza.
TK ???? Pendiente definir lo que sucede cuando se actualiza ERPNext. Es probable que sea necesario realizar copia de respaldo?
	> /home/frappe/frappe-bench/apps/erpnext/erpnext/[nombre_del_modulo]/doctype/[nombre_del_doctype]/templates/

###### 8 Solamente para productos
No es necesario habilitar developer mode!
Solamente hay que configurar **Product Settings** desde el awesome bar

1. Vaya al Awesome Bar y escriba esto: **Product Settings**
2. Haca clic en la caja de selección: **Pagina principal es productos** (Debe estar seleccionada o tener cheque)
3. Haga clic en la caja de selección **Mostrar Productos como una Lista** (Debe estar seleccionada o tener cheque)
4. Indique cuantos productos desea mostrar por página.

###### ----- Pendiente de Limpieza o asignación IGNORE ESTA SECCION ----
When modifying the top bar in **Website Settings**, be careful about the background definition, it will block it. Instead, modify the CSS file!
Make sure the CSS is properly formatted and names adequately typed.


NO FUNCIONA!! en Theme > HTML Header & Robots
La mejor manera de modificar elementos individuales HTML de su pagina web es usar el inspector
con esto podra ver los **Elements** de la página HTML, los cuales puede modificar mediante referencias a su **clase o Class**
de CSS.  Este CSS debe de ser colocado en el campo:

`<head>` HTML
Y declare el CSS así:
`<style>[estilos CSS van aqui adentro.]</style>`
Por ejemplo para modificar la barra superior del menu, en **Website Theme** , bajo **Apply Text Styles** ingrese:
```<style>
.navbar {background-color: #6cc04a;}

.navbar .nav > li > a {
	color: #fff;
}

.navbar 
.nav > li {margin-top: 50px;}
</style>

```
 
Para enlazar archivos para la web, adjuntelos a "public"  y luego refiera a ellos como:
<img src="/files/image_name.png" style="height:18px">

Para que los enlaces en la barra superior esten ajustados, o centrados, agregue este estilo

Puede compartir el DocType completo en el sitio web, indicando en su configuración:  Has Web View como "marcar".
Tambien indique "Allow Guest To View" para que pueda verlo.
Coloque la ruta  **Route** para
###### ----- Pendiente de Limpieza o asignación IGNORE ESTA SECCION ----

### 2.3 Conclusión Modulo 2

En este módulo hemos aprendido lo más importante de ERPNext.
Vimos la operativa básica del programa: hacer login, configurar su usuario, configurar sus iconos del escritorio, seleccionar su idioma, acceder al menu de configuración del programa en donde agregamos un usuario.
También conocimos el importantisimo marco Frappé, que es lo que hace tan poderoso a ERPNext,
 con sus tipos de documentos principales y de apoyo, y su funcionalidad que permite asignar 
 documentos a otros usuarios, adjuntar archivos a estos documentos, compartir documentos 
 individuales cuyos permisos estan restringidos a ciertos usuarios, llevar seguimiento 
 cronológico de las actividades realizadas sobre un DocType y sus autores así como los 
 comentarios que se pueden colocar directamente al DocType.  También vimos donde encontrar 
 soporte y ayuda.

Luego iniciamos nuestra exploracion de los modulos de contabilidad, creando una compañía,
creando los centros de costo, creando cuentas contables y conociendo como se crean partidas contables.
Vimos el módulo de recursos humanos donde creamos el primer empleado.  Luego pasamos al 
modulo de bodegas o almacén, donde aprendimos la importancia de agrupar productos, vimos
un ejemplo de un esquema de codificacion, creamos un par de bodegas y luego aprendimos a
crear articulos. El artículo es la base más importante del sistema ERPNext.

Posteriormente pasamos a conocer el modulo de compras donde creamos un proveedor, modificarlo,
 hacer la primera cotizacion, luego una compra directa, y finalmente una compra mas formal con 
 cotizacion, orden de compra, recibo de compra, factura y pago

Luego vimos lo mismo solamente que en el modulo de Ventas, en donde agregamos un cliente,
 modificamos un cliente, ingresamos una cotización al cliente, luego realizamos nuestra primer
 venta directa, y luego realizamos una venta mas formal.

Vimos el modulo de CRM o manejo de clientes, que nos permite mejorar la atencion
al cliente, crear campañas publicitarias, y rastrear las iniciativas hasta que se convierten 
en clientes.

Revisamos el modulo de manufactura y una de las bases de este modulo: El **Listado de Materiales (LdM)**
que nos permite definir la materia prima necesaria para un producto especifico.

El modulo de proyectos se revisó, con la creación de un proyecto interno con tareas y fechas limite.
El modulo de Bienes con sus categorias y Activos (Bienes), que aprenderemos como se deprecian automaticamente y se les puede
registrar mantenimiento en el siguiente modulo.
El modulo de sitio web nos permitio crear una simple pñagina web para servir a todos los usuarios 
que accesan nuestro sitio desde la web.

## Módulo 3: Uso Intermedio
### 3.1 Operación Intermedia
#### 3.1.1 - Roles (Video 039)
#### 3.1.2 - Permisos (Video 040)
#### 3.1.3 - Secuencias e Identificadores (Series) (Video 041)
#### 3.1.4 - Ajustes del sistema (Video 042)
#### 3.1.5 - Ajustes globales (Video 043)
#### 3.1.6 - Ajustes de las cuentas (Video 044)
#### 3.1.7 - Configurando cuenta de correo electronico (Video 045)
#### 3.1.8 - Ajustes de impresión (Video 046)
#### 3.1.9 - Traducciones personalizadas (Video 047)
#### 3.1.10 - Otros ajustes  (Setup Module) MORE WORK NEEDED HERE
### 3.2 Modulos del programa
#### 3.2.1 - Cuentas Contables
##### 3.2.1.1 - Año fiscal  (Video 048)
##### 3.2.1.2 - Monedas (Video 049)
##### 3.2.1.3 - Configuración del POS (Video 050)
##### 3.2.1.4 - Formas de pago (Video 051)
##### 3.2.1.5 - Entrada de pago (Video 057)
##### 3.2.1.6 - Impuestos (ventas) (Video 053)
##### 3.2.1.7 - Impuestos (compras) (Video 054)
##### 3.2.1.8 - Factura de venta (Video 055)
Descuentos: Si aplica un porcentaje de descuento sobr eel Gran Total, el total será:
(Suma de producto x cantidad - Impuesto de Ventas(incluido)) - ((Suma de producto x cantidad - Impuesto de Ventas(incluido)) * % Descuento)

Si usted aplica un monto de descuento toal sobre el gran total, el total será:
(Suma de producto x cantidad - Impuesto de Ventas(incluido) - (Monto de Descuento))
##### 3.2.1.9 - Factura de compra (Video 056)
##### 3.2.1.10 - Conciliando pagos (Video 057)
##### 3.2.1.11 - Subscripciones SIN VIDEO
El módulo se subscripciones en ERPNext le permite crear automáticamente documentos con
periodicidad.
Se puede crear subscripciones para documentos como:

* Entrada de Pago
* Cotizacion de Proveedor
* Orden de Compra
* Factura de Compra
* Recibo de Compra
* Partida Contable
* Orden de Venta
* Factura de Venta
* Cotizaciones a Clientes
* Notas de Entrega

Los documentos serán creados automáticamente en el momento indicado, en estado de *Borrador*
Usted puede indicar si desea que se validen automáticamente al momento de ser creados!

Supongamos que usted debe crear una factura de pago por el alquiler mensual manualmente.
Con subscripciones, usted puede crear la primer factura mensual, y luego habilitar la subscripcion
para que se genere automáticamente la factura de compra cada mes, en el día que usted elije

###### 3.2.1.11.1 - Creando una subcripcion
1. Para poder crear una subscripción, debe tener por lo menos un documento creado del tipo de documento que desea repetir.
	si no lo ha hecho, prepare el primero y guárdelo.
2. Para crear la subscripción escriba esto en la barra superior que muestra ERPNext llamada "*Awesome Bar*": **New Subscription**
3. Ingrese el **Tipo de Documento** de referencia para su subscripción
4. Ingrese la serie y número del documento que desea repetir, este es el documento que creo en el paso 1
5. Seleccione la frecuencia que desea para la subcripción, esta puede ser:
	* Diario
	* Semanal
	* Mensual:  Debe indicar el día del mes específico en que desea que se repita.
	* Trimestral: Debe indicar el día específico del mes en que se cumple el trimestre en que desea que se repita.
	* Semestral
	* Anual: Debe indicar el día especifico del mes en que se cumple el año en que desea que se repita.
6. Indique la fecha a partir de la cual se debe de crear el primero de la serie
7. Indique la fecha a partir de la cual ya no se crearán más documentos automáticos
	* Si la fecha final es antes de la siguiente fecha estimada en la frecuencia, el programa
	limitará la creación del documento.
8. Indique si desea que el documento se *Valide* al momento de la creación
	* Si usted desea automáticamente facturarle a un cliente, y tiene un envío automático
	indique que si en este campo, para que se genere la factura y el envío automático.
9. Indique si desea deshabilitar la subscripción (aunque no desee borrarla)
10. Indique si desea que se emita una notificación por correo electrónico. Al seleccionar el campo,
	deberá indicar lo siguiente:
	* Tema del correo: Puede indicar con formato Jinja, un mensaje dinámico como "Nueva Factura de Venta # 123",
	en donde 123 es el número del documento creado por la subscripción.
	* Recipientes del correo, separados por una linea nueva. Puede agregar cuantos recipientes desee
	* Formato de Impresión
	* Mensaje: El mensaje del correo deseado, donde podra indicar con formato Jinja, mensajes de tipo dinamico con numeros, nombres de cliente, etc.
#### 3.2.2 - Recursos Humanos
##### 3.2.2.1 - Configuracion de recursos Humanos (Video 058)
##### 3.2.2.2 - Lista de festividades (Video 059)
##### 3.2.2.3 - Estructura salarial y componentes (Video 060)
##### 3.2.2.4 - Nómina Salarial (Video 061)
##### 3.2.2.5 - Herramienta para crear boletas de pago (planilla) (Video 062)
##### 3.2.2.6 - Configuracion de ajustes del resumen diario de trabajo (Video 063)
#### 3.2.3 - Almacén o Inventario
##### 3.2.3.1 - Unidades de Medida (Video 064)
##### 3.2.3.2 - Marcas (Video 065)
##### 3.2.3.3 - Configuración de inventarios (Video 065)
##### 3.2.3.4 - Configuracion de Variantes de Articulo (Producto) (Video 209)
##### 3.2.3.5 - Lista de Precios (Video 066)
##### 3.2.3.6 - Entradas de Inventario (Movimiento de bodegas) (Video 067)
* Carga inicial a inventario
	1. Almacen
	2. Entradas de Inventario
	3. Clic en nuevo
	4. Propósito: Recepción de materiales
	5. Indicar Almacen de destino Predeterminado
	6. Ingresar el nombre o codigo del producto,  en donde dice:  Codigo del producto.
	7. Indicar la cantidad a dar de alta o cargar en inventario.
	8. Repetir para cada producto deseado
	9. Si no se indico valor neto de IVA en el Producto,  se lo pedira.
	10. Clic en guardar, y luego Validar
##### 3.2.3.7 - Partida de apertura de inventario (Video 068)
##### 3.2.3.8 - Solicitud de Materiales (Video 069)
##### 3.2.3.9 - Recibo de Compra (Video 070)
#### 3.2.4 - Compras
##### 3.2.4.1 - Configuración de Compras (Video 071)
##### 3.2.4.2 - Conjunto / Paquete de productos (Video 001)
 Importante:  Si cambio la bodega por omision de ERPNext DESPUES de haber creado un conjunto de productos, asegurese de refrescar o recargar el servidor.
##### 3.2.4.3 - Términos y condiciones compras (Video 072)
##### 3.2.4.4 - Tarjeta de puntuacion de proveedores (Video 073)
##### 3.2.4.5 - Criterios de Calificación del proveedor (Video 074)
##### 3.2.4.6 - Variable de Calificación del proveedor (Video 075)
#### 3.2.5 - Ventas
##### 3.2.5.1 - Configuración de Ventas (Video 076)
##### 3.2.5.2 - Tipo de industria (Video 077)
##### 3.2.5.3 - Territorio (Video 078)
##### 3.2.5.4 - Socio de Ventas (Video 079)
##### 3.2.5.5 - Vendedores (Video 080)
##### 3.2.5.6 - Conjunto / Paquete de productos (Video 001) - Revisado
##### 3.2.5.7 - Terminos y condiciones Ventas (Video 081)
##### 3.2.5.8 - Venta mediante POS (Video 082)
##### 3.2.5.9 - Regla de Precios NO VIDEO
1. Puedes establecer promociones en las cuales ofrece descuento en la compra de x cantidad de articulos
2. Para cliente X, el precio de venta debe ser actualizado por y cantidad
3. Los productos categorizados bajo el Grupo de Articulos especificado tienen el mismo precio de ocmpra o venta.
4. Los clientes que pertenecen a un grupo especifico de clientes obtienen precio de venta x o un descuento del y %
5. Los proveedores bajo cierta categoría deben de tener un precio x.
6. Puedes agregar margen de venta sobre lista de compras
	6.1 Haga un listado de precios de compra y asegurese de ingresar un precio de compra en ese listado
	6.2 Haga una regla de precio en la cual indique el codigo del articulo de compra. Indique que es una regla para la venta.
	6.3 Agregue el margen porcentual que usted desea sobre el producto de compra
	6.4 Haga su factura de venta y verá el margen aplicado.
Si desea alterar precios masivamente, se sugiere utilizar una hoja de excel e ingresarlos todos nuevamente.
#### 3.2.6 - CRM (Manejo de Recursos: Clientes)
##### 3.2.6.1 - Categoría de Cliente (Video 083)
##### 3.2.6.2 - Comunicaciones (Video 084)
##### 3.2.6.3 - Ajustes SMS o mensajería móvil desde ERPNext (Video 085)
#### 3.2.7 - Manufactura
##### 3.2.7.1 - Subcontratación (Video 086)
La subcontratación permite administrar aquellos productos que usted vende 
pero que un proveedor le ensambla, pero al cual usted le provee materia prima de sus bodegas.

Si usted ya ha configurado algunos productos para la venta en ERPNext, 
puede agregarles un identificador como producto subcontratado para facilitarle los pedidos
al proveedor.

###### 3.2.7.1.1 - Producto subcontratado
###### 3.2.7.1.2 - Listado de Materiales para Producto subcontratado
###### 3.2.7.1.3 - Bodega para el Proveedor Subcontratado
###### 3.2.7.1.4 - Orden de Compra con subcontratación
###### 3.2.7.1.5 - Orden de Compra con subcontratación
###### 3.2.7.1.6 - Orden de Compra con subcontratación

##### 3.2.7.2 - Orden de Produccion (Video 087)
##### 3.2.7.3 - Registro de Horas (Video 088)
#### 3.2.8 - Proyectos
##### 3.2.8.1 - Tipos de Proyecto (Video 089)
##### 3.2.8.2 - Tipo y Costo de Actividad (Video 090)
##### 3.2.8.3 - Tareas de Proyectos (Video 091)
La tarea es una asignación de trabajo para ser completada antes de un momento específico.
Una tarea puede existir por sí sola, o puede estar enlazada con un proyecto. 
Si desea ver como se crea una tarea desde un proyecto, siga las instrucciones desde el proyecto.

Para hacer una nueva Tarea, vaya a **Proyectos > 	Tareas > Nueva**
Ingrese el *Asunto* o *Título* de la tarea.
Seleccione si pertenece a un proyecto, si es necesario
Ingrese la fecha prevista de Inicio y Fin
Puede ingresar el *Tiempo esperado* de la tarea en horas.
Tambien puede ingresar el progreso en *Porcentaje*
Indique los detalles específicos de esta tarea textualmente

Si esta tarea depende de otra tarea, puede indicarlo aquí

Puede asignar o compartir la tarea con sus colegas

##### 3.2.8.4 - Registro de Horas (Video 092)  
Para registrar el tiempo usado en una tarea, creamos un registro de horas
Seleccione el tipo de actividad
Indique la hora de inicio
Indique las horas usadas
Se actualiza la hora de finalizacion
Guarde el registro.

En la tarea relacionada al registro de tiempo, podrá ver el tiempo invertido en esta tarea
Si la tarea pertenece a un proyecto, entonces también se actualizará el tiempo invertido alli.

#### 3.2.9 - Bienes o Activos
##### 3.2.9.2 Equipo de mantenimiento de activos (Video 093)
##### 3.2.9.3 Mantenimiento de activos (Video 094)
##### 3.2.9.4 Registro de mantenimiento de activos (Video 095)
##### 3.2.9.5 Reparación de activos (Video 096)
#### 3.2.10 - Herramientas
##### 3.2.10.1 - Tareas (Video 097)
##### 3.2.10.2 - Archivos (Video 098)
##### 3.2.10.3 - Calendario (Video 099)
##### 3.2.10.4 - Chat (Video 100)
##### 3.2.10.5 - Nota (Video 101)
##### 3.2.10.6 - Actividad (Video 102)
##### 3.2.10.7 - Grupo de Correo electronico (Video 103) 
##### 3.2.10.8 - Boletín de noticias (Video 104)
#### 3.2.11 - Sitio Web
##### 3.2.11.1 - Configuracion del Sitio Web (Video 105)
##### 3.2.11.2 - Configuración de información de la compañía (Video 106)
##### 3.2.11.3 - Configuración de contácto (Video 107)
##### 3.2.11.4 - Tema del sitio web (Video 108)
##### 3.2.11.5 -  Configuración del portal (Video 109)
##### 3.2.11.6 - Página Principal (Video 110)
##### 3.2.11.7 - Configuracion del Blog (Video 111)
##### 3.2.11.8 - Entrada en el Blog (Video 112)
### 3.3 Conclusión Modulo 3

## Modulo 4: Uso avanzado
Que veremos aquí
### 4.1 Operación Avanzada
#### 4.1.3 - Ajustes específicos por Dominio
##### 4.1.3.1 - Modulo Agricultura (Video 113)

##### 4.1.3.2 - Modulo de Hospitalidad (Video 114)

##### 4.1.3.3 - Modulo de Salud (Video 115)
Presentacion del modulo de salud, enlace a modulo 12 con detalles
##### 4.1.3.4 - Modulo de Educacion (Video 116)
Presentacion del modulo de educacion, enlace a modulo 10 con detalles.
##### 4.1.3.6 - Modulo de Servicios (Video 117) 
Preparar algun video de flujo de trabajo de servicios o mejores practicas.
##### 4.1.3.7 - Modulo de Manufactura (Video 118)
Preparar algun video de flujo de trabajo de manufactura o mejores practicas.
##### 4.1.3.8 - Modulo de Conexión para Shopify (Video 148) [Seminario Web Shopify/ERPNext](https://youtu.be/sd2p-0jATzc) 
Con esta integración a ERPNext:
* Cuando agrega un **Producto** o **Cliente** a una cuenta de Shopify, se sincroniza con ERPNext automaticamente.
* Si agrega un nuevo **Producto** o **Cliente** en su cuenta de ERPNext, se sincronicará automaticamente con Shopify.
* Usted puede realizar manualmente la sincronización de **Productos** o **Clientes**.
* Puede recibir los pedidos de clientes de Shopify directamente en ERPNext.
Requisitos:
* Cuenta de Shopify
* Servidor ERPNext con dominio: p. ej. su-dominio.com

###### 4.1.3.8.1 - Pasos de Configuracion en ERPNext para simplifcar
1. Prepare un **Listado de Precios** en ERPNext específicamente para los Productos que venderá en **Shopify**, si desea.
2. Prepare un **Almacén** en ERPNext para los **Productos** que llevará registro del inventario de ventas para **Shopify**
3. Prepare una **Cuenta** en donde los depósitos de las ventas de **Shopify** se registrarán, bajo activos corrientes o de corto plazo.
4. Prepare una Secuencia y Serie especifica para las *Órdenes de Venta* que creará con Shopify, si desea diferenciarlas de otras *Órdenes de Venta*.
5. Prepare una Secuencia y Serie especifica para las *Notas de Entrega*, si desea diferenciarlas de otras *Notas de Entrega*.
6. Prepare una Secuencia y Serie especifica para las *Facturas de Venta*, si desea diferenciarlas de otras *Facturas de Venta*.

###### 4.1.3.8.2 - Agregue la aplicación de ERPNext a su cuenta de Shopify
* En la pantalla de administración de su cuenta de Shopify, en la parte de abajo verá un enlace que dice **Apps**
* Haga click en el enlace para abrir la tienda de aplicaciones de Shopify.
* Busque la aplicación llamada: **ERPNext Connector**
* Haga click en **Get** para instalar en su cuenta de Shopify
	Esta ventana le notificara que ERPNext podrá hacer lo siguiente:
	* Modificar productos, variantes y colecciones.
	* Modificar detalles de cliente y grupos de clientes
	* Modificar pedidos, transacciones y entregas o cumplimientos

* Clic en **Install App**
* Ingrese los datos requeridos:
	*Shop Name*: Ingrese el nombre de su tienda web como se lo proporciona Shopify:  [su-tienda].shopify.com
	*ERPNext Site Name*: Este es el nombre de dominio en el cual esta corriendo ERPNext. Ejemplo: sitioprueba.com
	*ERPNext User Id*: Ingrese el ID de usuario (direccion de correo electrónico) del usuario que tendra acceso a sincronizar.
	*Password*: La contraseña asociada con el usuario de ERPNext indicado arriba.
* Clic en el botón de **Submit**
* El sitio de Shopify debería de mostrar que se instaló correctamente la aplicación de ERPNext bajo el subtítulo: **Installed apps**
###### 4.1.3.8.2 - Configure ERPNext para que se conecte a Shopify
Idealmente, el servidor de ERPNext se actualizará automáticamente para agregar la aplicación de Shopify.
Si no es el caso, asegúrese de instalar la aplicación en: **Configuración > Aplicaciones > Instalador de Aplicaciones > ERPNext Shopify**

1. Para acceder a la configuración de Shopify escriba esto en la barra superior que muestra ERPNext llamada "*Awesome Bar*": **Shopify settings**
2. Asegurese que la caja para marcar titulada **Enable Shopify** este marcada.
3. *App Type*: **Public**
4. *Shop URL*: Ingrese el nombre de la tienda Shopify como lo tiene arriba **[your_store].shopify.com**
5. *Price List*: Seleccione el listado de precios de ERPNext que utilizará por default.
6. *Warehouse*: Seleccione el almacén de donde despachará los **Productos** que se pidan en Shopify.
7. *Cash/Bank Account*: Confirme la cuenta de ERPNext que registrará contablemente los depositos de las ventas de Shopify.
8. *Customer Group*: Aunque esto se configura automáticamente desde Shopify, lo puede colocar manualmente aqui.
9. *Sales Order Series*: Eliga la Secuencia y serie para generar automáticamente cuando un pedido de Shopify se sincronize con ERPNext
10. Conecte categoría de Impuesto y Costos de Envío a su cuenta respectiva de ERPNext.
	10.1 Agregue una fila en donde define el Título del Impuesto o cargo de Costo de Envío.
	10.2 En la misma fila, seleccione la cuenta de ERPNext en donde usted desea contabilizar estos cargos
	10.3 El **Titulo** debe ser igual al nombre de los rubros adicionales en el pedido o factura de Shopify. ??? TK
11. *Import Delivery Notes from Shopify on Shipment* (Importe las Notas de Entrega al Despachar Envío):  
	Si desea crear una **Nota de Entrega** basado en los productos marcados como enviados en Shopify.
	11.1 Debe seleccionar la serie de **Nota de Entrega** que desea para que esto funcione adecuadamente.
12. *Import Sales Invoice from Shopify if Payment is marked* (Importe las Facturas de Venta si hay Pago Realizado): 
	Si desea crear una **Factura de Venta** en ERPNext si la factura de SHopify indica que ya fue pagada.
	12.1 Debe seleccionar la serie de **Factura de Venta** que desea para que esto funcione adecuadamente.
	
###### 4.1.3.8.3 - Sincronice Productos de Shopify a ERPNext
1. Desde ERPNext, para sincronizar manualmente vaya a 
	**Shopify settings** ingresando el texto en la barra superior "*Awesome Bar*" y haga clic en **Sync Shopify** (Sincronizar Shopify)
2. Un mensaje saldrá indicando: 
	*"Queued for syncing. It may take a few minutes to an hour if this is your first sync."*
	*(En cola para sincronizar. Puede tomar unos minutos hasta una hora si esta es su primer sincronización)*
3. En la misma página le mostrará un indicador amarillo, haciéndole ver que:
	*"The Last sync request is queued"*
	*(La última solicitud de sincronización esta en cola)*
	Este mensaje cambiará a:
	*Last sync request was successful*
	*(La ultima solicitud de sincronización fue exitosa)*
	Cuando haya finalizado exitosamente la última sincronización.
4. Si presiona el botón de **Shopify Log** (Bitácora de Shopify), podrá ver todos los registros de
	sincronización con su título como un a pre-confirmación del estatus y su estatus como
	*Exitoso* o **Falló*
5. Si ahora va a **Almacén > Productos**, usted verá los Productos recién sincronizados desde Shopify.
	Cada producto estará identificado con una serie numérica: **Shopify Product ID** (Identificador de Producto Shopify), y también
	verá las características que obtuvo de Shopify como Descripción, Imagen, etc.

###### 4.1.3.8.4 - Sincronice Productos de ERPNext a Shopify
1. Vaya a **Almacén > Productos** y abra cada Producto que desea sincronizar hacia Shopify
2. Cada **Producto** tiene una caja para marcar que indica **Sync With Shopify** (Sincronizar con Shopify). Asegúrese de marcar esta caja y 
	**Guarde** el **Producto** para confirmar los cambios.
3. Si tambiñen desea sincronizar las existencias en su Almacén de ERPNext hacia Shopify, entonces
	marque la caja **Sync Quantity With Shopify** (Sincronizar Cantidad/Existencias con Shopify).
	No olvide, **Guardar** el **Producto** para confirmar los cambios.
4. Vaya a **Shopify settings** y haga clic en **Sync Shopify** (Sincronizar Shopify) nuevamente para empujar la data de los Productos de ERPNext a Shopify.
5. Si usted visita su página de productos en Shopify, usted verá los productos que acaba de sincronizar desde ERPNext.

###### 4.1.3.8.5 - Sincronice Clientes desde Shopify a ERPNext
1. En **Shopify**, puede agregar clientes que se sincronizan con ERPNext automáticamente.
2. En **ERPNext** vaya a **Shopify settings** y haga clic en **Sync Shopify** para sincronizar clientes.
3. Toda la data, incluyendo direcciones, será sincronizada a cada cliente en **Clientes** de ERPNext.
###### 4.1.3.8.6 - Sincronice Clientes desde ERPNext a Shopify
Para Sincronizar un **Cliente** desde **ERPNext** a **Shopify**:

1. Abra el documento del **Cliente** deseado.
2. Navegue hacia abajo en la página y en la sección de **Más Información** marque la caja titulada: **Sync With Shopify** (Sincronizar con Shopify)
3. **Guarde** el **Cliente** para confirmar los cambios.
4. Vaya a **Shopify settings** y haga clic en **Sync Shopify** para copiar el Cliente a Shopify.

###### 4.1.3.8.7 - Sobre las Ordenes de Venta o Pedidos
Los pedidos se sincronizan solo de una vía: Desde Shopify hacia ERPNext.
> ERPNext solo obtiene o jala pedidos de Shopify!
Sus clientes "de cliente a empresa" hacen sus pedidos en **Shopify**, no en el portal de ERPNext.
Sus clientes "de empresa a empresa" pueden hacer sus pedidos en su portal de ERPNext configurado para el efecto.
Aunque tenga productos mostrados en su sitio web originando de ERPNext, el enlace para colocar un pedido debe llevarlo a su tienda Shopify
Media vez el pedido se ha hecho por el cliente, el pedido se sincronizará automáticamente hacia ERPNext.
Una orden de venta creada en ERPNext no se sincronizará a **Shopify**. Solamente obtendrá ordenes de venta desde **Shopify** hacia **ERPNext**.
###### 4.1.3.8.8 - Notas de Entrega
Si la caja para marcar **Notas de Entrega** esta seleccionada, ERPNext los sincrinizará y enlazará automáticamente
a **Ordenes de Venta**, **Facturas de Venta** o **Pagos**, en caso exista alguno.
Las **Notas de Entrega** tendrán dos campos de datos: El **Shopify Order ID** (Identificador de Pedido de Shopify) y **Shopify Fulfillment ID** (Identificador de Entrega Completa Shopify) cuando se sincronizen en Shopify.
Las **Notas de Entrega** de la sincronizacion quedarán **siempre** en estatus de **Borrador** para que pueda editarlas manualmente antes de validarlas.
Una **Nota de Entrega** validada por un usuario de ERPNext que cumple con el pedido de **Orden de Venta** o la **Factura de Venta** significa que el pedido ha sido cumplido a su enteridad.
Muy importante: Una **Nota de Entrega** creada primero en ERPNext, NO se sincronizará a Shopify! Solamente funciona desde **Shopify** hacia **ERPNext**.
###### 4.1.3.8.9 - Facturas de Venta
Si la caja de selección de **Factura de Venta** se selecciona en los ajustes de Shopify, ERPNext creará la **Factura de Venta** automáticamente.
Estas **Facturas de Venta** estarán enlazadas a **Notas de Entrega**, **Ordenes de Venta** y **Pagos** en caso existan.
Si el pagop ha sido recibido en **Shopify**, se creará un **Pago** automáticamente en ERPNext.

###### 4.1.3.8.10 - Algunas notas adicionales
Cuando los Productos se sincronizan de Shopify, el identificador único de Shopify es copiado a ERPNext.
Esto sirve para que no se sincronize mas de dos veces a Shopify desde ERPNext en la sincronización.
El listado de precios también se actualiza cuando se sincronizan productos y pedidos de Shopify.

La aplicación Shopify tiene una configuración del calendarizador de linux que sincronizará shopify frecuentemente (Tiempos precisos?)

Preguntas pendientes de responder: 
Que sucede si el impuesto sobre el valor agregado (IVA) ya está incluido en el precio de venta en Shopify?
Como se procesa un retorno de un cliente?:
1. Con reembolso?
2. Sin reembolso?

#### 4.1.2 - Copias de respaldo de datos (Video 149)
#### 4.1.3 - Personalización de formularios (Video 150)
	Agregando nuevos campos a doctypes principales (Customize)
#### 4.1.4 - Campos personalizados (Video 151)
		Nombre de campos anteponiendo nombre de su empresa (buena practica para evitar errores de actualizacion)
		Este sirve para doctypes hijos solamente!
#### 4.1.5 - Codigo fuente personalizado (Video 152)
#### 4.1.6 - Notificaciones de correo (Video 153)
#### 4.1.7 - Formatos de impresión (Video 154)
	Jinja Basico para plantillas de impresion
#### 4.1.8 - Estilo de impresión (Video 155)
#### 4.1.9 - Constructor de formato de impresión (Video 156)
### 4.1.10 - Formato de dirección (Video 157)

### 4.2 Modulos del programa
#### 4.2.1 - Cuentas Contables
##### 4.2.1.1 - Balanza de comprobacion (Video 158)
##### 4.2.1.2 - Solicitud de pago (Video 159)
##### 4.2.1.3 - Cuentas por cobrar (Video 160)
##### 4.2.1.4 - Cuentas por pagar (Video 161)
##### 4.2.1.5 - Estados de conciliacion bancarios (Video 162)
##### 4.2.1.6 - Resumen de cambios bancarios (Video 163)
##### 4.2.1.7 - Garantia bancaria (Video 164)
##### 4.2.1.8 - Regla fiscal (Video 165)
##### 4.2.1.9 - Presupuesto (Video 166)
##### 4.2.1.10 - Variacion de presupuesto (Video 167)
##### 4.2.1.11 - Distribucion mensual  para Presupuesto(Video 168)
##### 4.2.1.12 - Cierre de periodo (Video 169)
#### 4.2.2 - Recursos Humanos
##### 4.2.2.1 - Asistencia (Video 170)
##### 4.2.2.2 - Herramienta de Asistencia de los empleados (Video 171)
##### 4.2.2.3 - Subir asistencia (Video 172)
##### 4.2.2.4 - Solicitud de licencia (para ausentarse) (Video 173)
##### 4.2.2.5 - Tipo de licencia (para ausentarse) (Video 174)
##### 4.2.2.6 - Asignacion de vacaciones (Video 175)
##### 4.2.2.7 - Herramienta de asignación de vacaciones (Video 176)
##### 4.2.2.8 - Lista de bloqueo (Video 177)
#### 4.2.3 - Almacén o Inventario
##### 4.2.3.1 - Atributos de producto (Video 178)
##### 4.2.3.2 - Variantes de producto (Video 179)
##### 4.2.3.3 - Conciliacion de inventario (Video 180)
Una conciliacion de inventario le permite indicar los articulos o productos que han sido fisicamente contados
u observados en una bodega en una fecha específica, y la cuenta contable para aplicar como gasto aquellos
articulos que no ha encontrado. Usted puede especificar un centro de costo para esta conciliación.

Cada linea indica el articulo o producto, la bodega en donde se realizó la verificación, y el monto verificado en 
la bodega.
ERPNext obtendrá el valor de valuación (o lo puede ingresar usted mismo?)
Media vez haya validado la Conciliación de Inventario, se crearán las partidas de Inventario y en el libro mayor de Contabilidad.

Puede hacer cuantas conciliaciones de inventario usted desee.
##### 4.2.3.4 -  Lista de embalaje (empaque) (Video 181)
##### 4.2.3.5 - Numero de serie (Video 182)
##### 4.2.3.6 - Numero de lote (Video 183)
#### 4.2.4 - Compras
##### 4.2.4.1 - Invitando a proveedores al portal ERPNext de su empresa (Video 184)
Al crear una solicitud de cotización, puede invitar al proveedor a su portal para que realice una oferta
sobre la solicitud.

##### 4.2.4.2 - Ingreso de cotizaciones de proveedor al portal ERPNext de su empresa (Video 185)
#### 4.2.5 - Ventas
##### 4.2.5.1 - Regla de envío (Video 186)
##### 4.2.5.2 - Analisis de ventas (Video 187)
##### 4.2.5.3 - Compras y lealtad de clientes (Video 188)
#### 4.2.6 - CRM (Manejo de Recursos: Clientes)
###### 4.2.6.1 - Registro SMS (Video 189)
###### 4.2.6.2 - Ajustes de SMS (Video 190)
#### 4.2.7 - Manufactura
##### 4.2.7.1 - Ordenes de producción abiertas (Video 191)
##### 4.2.7.2 - Ordenes de produccion en progreso (Video 192)
##### 4.2.7.3 - Productos entregados desde ordenes de producción (Video 193)
##### 4.2.7.4 - Ordenes de producción (OP) completadas (Video 194)
##### 4.2.7.5 - Analisis de producción (Video 195)
#### 4.2.8 - Proyectos
##### 4.2.8.1 - Resumen diario de horas (Video 196)
##### 4.2.8.2 - Seguimiento preciso del stock (Video 197)
##### 4.2.8.3 - Informe o Gráfico de Gantt NO VIDEO
Este informe muestra las tareas sobrepuestas contra un calendario
para visualizar el tiempo requerido para completar la tarea.

Se puede actualizar el progreso de la tarea (%) desde el gráfico de Gantt

La dependencia de una tarea sobre la otra se vera reflejada con una flecha

#### 4.2.9 - Bienes o Activos 
##### 4.2.9.1 - Movimiento de activo (Video 198)
##### 4.2.9.2 - Depreciaciones de Activos y Saldos (Video 199)
### 4.3 Conclusion Modulo 4
Que vimos aquí

## Modulo 5: Convirtiendose en experto
Qué veremos aquí
### 5.1 Operación nivel experto
#### 5.1.1 Instalador de aplicaciones (Video 200)
#### 5.1.2 Alertas de correo electronico (Video 201)
#### 5.1.3 Respuesta estandarizada (Video 202)
#### 5.1.4 Disparador de retroalimentación (Video 203)
#### 5.1.5 Resumen por correo (Video 204)
#### 5.1.6 Cuenta de pago vía Portal (Cuenta pasarela de pago) (Video 205)
#### 5.1.7 - Plantilla de impresión de cheques (Video 206)
#### 5.1.8 - Programando plantillas de factura avanzadas (Video 207)
### 5.2 Modulos del programa
#### 5.2.1 - Cuentas Contables
##### 5.2.1.1 - Beneficio bruto (Gross profit) (Video 208)
##### 5.2.1.2 - Tendencias de compras (por factura) (Video 209)
##### 5.2.1.3 - Tendencias de ventas (por factura) (Video 210)
##### 5.2.1.4 - Balance de terceros (Video 211)
##### 5.2.1.5 - Periodos de pago según facturas (payment period based on invoice date) (Video 212)
##### 5.2.1.6 - Comisiones de socio de ventas (Sales partner comission) (Video 213)
##### 5.2.1.7 - Detalle de ventas (Video 214)
##### 5.2.1.8 - Detalle de compras (Video 215)
##### 5.2.1.9 - Saldo de clientes (Video 216)
##### 5.2.1.10 - Saldo de proveedores - (Video 217)
##### 5.2.1.11 - Resumen de pago de ventas (Video 218)
##### 5.2.1.12 - Creando y Guardando Informes personalizados (Video 219)
#### 5.2.2 - Recursos Humanos
##### 5.2.2.1 - Evaluacion (Video 220)
##### 5.2.2.2 - Plantilla de evaluacion (Video 221)
##### 5.2.2.3 - Actualizaciones equipo (Video 222)
##### 5.2.2.4 - Programa de entrenamiento (Video 223)
##### 5.2.2.5 - Evento de capacitación (Video 224)
##### 5.2.2.6 - Resultado del Entrenamiento (Video 225)
##### 5.2.2.7 - Comentarios del Entrenamiento (Video 226)
##### 5.2.2.8 - Tipo de préstamo (Video 227)
##### 5.2.2.9 - Solicitud de prestamo del empleado (Video 228)
##### 5.2.2.10 - Prestamo de empleado (Video 229)
##### 5.2.2.11 - Vehiculo (Video 230)
##### 5.2.2.12 - Bitacora de Vehiculo (Video 231) 
##### 5.2.2.13 - Informes 
###### 5.2.2.13.1 - Cumpleaños del empleado (Video 232)
###### 5.2.2.13.2 - Balance de ausencias de empleado (Video 233)
###### 5.2.2.13.3 - Empleados que trabajan en un dia festivo (Video 234)
###### 5.2.2.13.4 - Informacion del empleado (Video 235)
###### 5.2.2.13.5 - Registro de salario (Video 236)
###### 5.2.2.13.6 - Hoja de asistencia mensual (Video 237)
###### 5.2.2.13.7 - Gastos del vehículo (Video 238)
#### 5.2.3 - Almacén o Inventario
##### 5.2.3.1 - Viaje de entrega (Video 239)
##### 5.2.3.2 - Inspección de calidad (Video 240)
##### 5.2.3.3 - Comprobante de costos de destino estimados (Video 241)
##### 5.2.3.4 - Nota de instalación (Video 242)
##### 5.2.3.5 - Vencimiento de Contrato de numero de serie (Video 243)
##### 5.2.3.6 - Estatus de Número de serie (Video 244)
##### 5.2.3.7 - Vencimiento de Garantía de Numero de Serie (Video 245)
##### 5.2.3.8 -  Informes de Stock o Inventario 
###### 5.2.3.8.1 - Mayor de inventarios (Video 246)
###### 5.2.3.8.2 - Balance de inventarios (Video 247)
###### 5.2.3.8.3 - Cantidad de inventario proyectado (Video 248)
###### 5.2.3.8.4 - Resumen de existencia (Video 249)
###### 5.2.3.8.5 - Antigüedad de existencias (Video 250)
###### 5.2.3.8.5 - Inventario por precios de producto (Video 251)
##### 5.2.3.9 -  Informes adicionales
###### 5.2.3.9.1 - Ordenes pendientes de entrega (Video 252)
###### 5.2.3.9.2 - Productos por recibir desde orden de compra (Video 253)
###### 5.2.3.9.3 - Reporte de productos con stock bajo (escasez) (Video 254)
###### 5.2.3.9.4 - Articulos solicitados para ser transferidos (Video 255)
###### 5.2.3.9.5 - Historial de saldo por lotes (Video 256)
###### 5.2.3.9.6 - Estado de caducidad de lote de productos (Video 257)
###### 5.2.3.9.7 - Precios de los productos (Video 258)
###### 5.2.3.9.8 - Nivel recomendado de reabastecimiento de producto (Video 259)
###### 5.2.3.9.9 - Detalles de la variante del articulo (Video 260)
#### 5.2.4 - Compras
##### 5.2.4.1 - Productos Para ser Solicitados (Video 261)
##### 5.2.5.2 - Requisiciones pendientes para ser ordenadas (Video 262)
##### 5.2.5.3 - Solicitudes de material para los que no hay presupuestos de proveedor (Video 263)
##### 5.2.5.4 - Historial de compras (Video 264)
##### 5.2.5.5 - Direcciones y contactos de proveedores (Video 265)
#### 5.2.5 - Ventas
##### 5.2.5.1 - Detalle de iniciativas (Video 266)
##### 5.2.5.2 - Direcciones de clientes y contactos (Video 267)
##### 5.2.5.3 - Ordenes pendientes de entrega (Video 268)
##### 5.2.5.4 - Resumen de transacciones por vendedor (Video 269)
##### 5.2.5.5 - Detalle de las Ventas (Video 270)
##### 5.2.5.6 - Buscar lista de materiales (LdM) (Video 271)
##### 5.2.5.7 - Clientes inactivos (Video 272)
##### 5.2.5.8 - Inventario Disponible de Artículos de Embalaje (Video 273)
##### 5.2.5.9 - Articulos pendientes en orden de venta para crear solicitud de compra (Video 274)
##### 5.2.5.10 - Saldo de clientes (Video 275)
##### 5.2.5.11 - Informes personalizados (Video 276)
#### 5.2.6 - CRM (Manejo de Recursos: Clientes)
##### 5.2.6.1 - Detalle de iniciativas (REPETIDO EN VENTAS) (Video 277)
##### 5.2.6.2 - "Embudo" de ventas (Video 278)
##### 5.2.6.3 - Prospectos comprometidos pero no convertidos (Video 279)
##### 5.2.6.4 - Minutos hasta la primera respuesta para Oportunidades (Video 280)
##### 5.2.6.5 - Clientes Inactivos (repetido en ventas) (Video 281)
##### 5.2.6.6 - Eficiencia de la campaña (Video 282)
##### 5.2.6.7 - Eficiencia del propietario de la iniciativa (Video 283)
#### 5.2.9 - Bienes o Activos
##### 5.2.9.1 - Movimiento de activo (Video 284)
##### 5.2.9.2 - Libro de Depreciacion de Activos (Video 285)
#### 5.2.10 - Mantenimiento del programa
##### 5.2.10.1 - Accesando linea de comandos - linux (Video 286)
##### 5.2.10.2 - Terminal iTerm (Video 287)
##### 5.2.10.3 - Haciendo snapshots (VirtualBox, u otras opciones) (Video 288)
##### 5.2.10.4 - Instalación en servidor remoto (Video 289)
##### 5.2.10.5 - Configurando SSL con Let's Encrypt (Video 290)
##### 5.2.10.5 - El folder de ERPNext: Frappe-Bench (Video 291)
##### 5.2.10.6 - Actualizando la Aplicación (Video 292)
##### 5.2.10.7 - GitHub y Versiones de control (Video 293)
##### 5.2.10.8 - Modo desarrollador y consola desarrollo del navegador (Video 294)

### 5.3 Conclusión Modulo 5

## Modulo 6: Manufactura (Temas pendientes o avanzados)
Ya se vieron anteriormente, pero aquí se pueden hacer videos especificos de ejemplos mas avanzados, o casos.
Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/manufacturing)

## Modulo 7: Servicios (Temas pendientes o avanzados)
Ya se vieron anteriormente, pero aquí se pueden hacer videos especificos de ejemplos mas avanzados, o casos.
Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/projects)

## Modulo 8: Ventas al detalle (Modulo de POS)
## 8.1 - Punto de Venta POS
### 8.1.1 - Como Funciona
### 8.1.2 - Configurando el Punto de Venta POS
### 8.1.3 - Como hacer una venta POS
### 8.1.4 - Usando sin conexión a Internet - Almacenaje de datos local

Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/accounts/point-of-sale-pos-invoice)

## Modulo 9: Stock Module Additional Topics
## 9.1 - Topicos de inventario y Distribución
### 9.1.1 - Retorno de compra
### 9.1.2 - Retorno de venta
### 9.1.3 - Inventario de muestra

Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/stock)

## Modulo 10: Educación
Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/education)
### 10.1 - Introduccion - ERPNext para escuelas - (Video 119)
https://youtu.be/f6foQOyGzdA
###10.2 - Aplicaciones de estudiantes - (Video 120)
https://youtu.be/l8PUACusN3E
### 10.3 - Administracion de estudiantes - (Video 121)
https://youtu.be/nIUsbl0rEE0
### 10.4 - Programas y Cursos - (Video 122)
https://youtu.be/1ueE4seFTp8
### 10.5 - Inscripcion a Programas - (Video 123)
https://youtu.be/5nxWYBRHY_o
### 10.6 - Instructores - (Video 124)
https://youtu.be/rVqQYS1_02k
### 10.7 - Grupos de Estudiantes (Secciones) - (Video 125)
Estudiantes que estan inscritos en un curso
https://youtu.be/5K_smeeE1Q4
### 10.8 - Agendar cursos - (Video 126) 
Se agenda para cada instructor y alumnos
https://youtu.be/iy-DBV9jI-A
### 10.9 - Asistencia de Alumnos - (Video 127)
https://youtu.be/j9pgkPuyiaI
### 10.10 - Solicitud de Ausencia - (Video 128)
https://youtu.be/NwwH5t-NKBE
### 10.11 - Criterios de Evaluación y Calificaciones - (Video 129)
https://youtu.be/t8ZDDq4qtIk
### 10.12 - Grupo de Evaluaciónes - (Video 130)
Un grupo de evaluacion, una jerarquia de evaluaciones realizadas en un año académico
https://youtu.be/I1T7Z2JbcP4
### 10.13 - Plan de Evaluaciones - (Video 131)
Agenda una evaluacion para un grupo especifico de alumnos en un curso especifico
https://youtu.be/Q9CzzoYb_Js
### 10.14 - Resultado de Evaluaciones - (Video 132)
El resultado de evaluaciones registra la calificacion del alumno en una evaluacion especifica. La herramienta de resultado de evaluaciones, le permite crear varios resultados de alumnos al mismo tiempo, basado en un plan de evaluacion.)
https://youtu.be/U8ZRB8CM-UM
### 10.15 - Estructura de Tarifas - (Video 133)
Categoria de tarifas y cuentas de tarifas (categoria de tarifas que se combina para calcular el total a cobrar por alumno. (Mensualidad, colegiatura, etc.)
https://youtu.be/_ZkvyVnWgYk
### 10.16 - Registro de Tarifas Masivo - (Video 134)
Registra multiples tarifas para grupos de alumnos al mismo tiempo.
### 10.17 - Tarifas y Pagos - (Video 135)
Como se crea una tarifa por alumno.  Y como registrar el pago recibido.
https://youtu.be/RfWOyjgxIZM

## Modulo 11: Agricultura
Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/agriculture)
### 11.1 Introducción de ERPNext para Agricultura
Toda operación agricola requiere registros detallados e intensivos si se desea tener una óptima cosecha.
Es importante par auna Granja el llevar en orden su contabilidad, planilla, proveedores, clientes y logística.
ERPNext ya le permite llevar un orden de toda esta data, y el módulo de agricultura le permite administrar sus actividades agrícolas.

### 11.2 Unidades de Producción y Manejo de Cultivos
No importa cual sea su cultivo o metodología, todas las actividades agricolas se llevan 
a cabo en **espacios físicos**, los cuales usted subdivide en piezas lógicas (Parcela, Manzana, Lote, Pante, etc.)
Además estas actividades requieren momentos específicos para realizarse (Plantado, Riego, Fertilización, etc.). Adicionalmente
esto se hace en conjunto con tomar muestras del medio ambiente y del cultivo para analizarlos. Finalmente,
se requiere informes que ayuden a interpretar toda esta información y ayuden a tomar decisiones.

### 11.3 Demostración de Agricultura
El módulo de agricultura en ERPNext le permite centralizar todas las operaciones de su Granja.
Los registros se detallan para cada campo, como caracteristicas geoespaciales y del suelo o sustrato.
Le permite:

* Administrar los espacios físicos en dodne planta sus cultivos.
* Planificar y Administrar sus cultivos
* Registrar datos de análisis
* Planificar actividades relacionadas con sus cultivos
* Registrar la venta del cultivo o transferencia a una bodega para procesamiento post-cosecha
* Ver informes.

### 11.4 - Uso básico
La clave para comprender el módulo se encuentra en los tres elementos más importantes del 
módulo agrícola:

1. Unidad de Cultivo
2. Cultivo
3. Ciclo de Cultivo

#### 11.4.1 - Unidad de Cultivo
Antes de sembrar sus plantas, usted necesita un espacio físico.
Este es representado aquí por **Unidad de Cultivo**
A la **Unidad de Cultivo** también se le conoce como:

* Parcela
* Terreno
* Pante
* Lote
* Cama
* División
* Chaco
* Chacra
* Fracción
* Parte
* Cable
* Trozo
* Zona
* Sector
* Segmento
* Solar
* Regadío
* Solar

#### 11.4.2 - Cultivo
Aqui define las caracteristicas del **Cultivo**. 
1. Se define el nombre del cultivo, especie, y otro datos importantes.
2. Los insumos necesarios: Por Ejemplo: Semilla, pilón o esqueje
3. Resultantes del cultivo: 
	3.1 Cantidad y Unidad de Medida de producto esperados al momento de la cosecha durante la vida útil del cultivo.
	3.2 Calendario esperado o planificado de actividades, cosecha, etc.

#### 11.4.3 - Ciclo de Cultivo
El **Ciclo de Cultivo** es una representación de un plantado *específico* de un **Cultivo**
en una **Unidad de Cultivo** específico. Indica la fecha de inicio, junto con las labores de distintos tipos programadas
y las fechas en que esta agendada su ejecución.  Un ciclo de cultivo tiene varios estados, entre ellos:

* Borrador: Un ciclo de cultivo creado pero que no tiene injerencia en las actividades normales de ERPNext.
* Planificado: Un ciclo de cultivo que ya esta agendado, pero cuya fecha de inicio es en el futuro o posterior a la fecha actual.
* Activo: Un ciclo de cultivo agendado, cuya fecha de inicio es igual o anterior a la fecha actual.
* Cerrado: Un ciclo de cultivo, el cual ha sido cerrado. No se puede registrar mas movimientos hacia con un ciclo de cultivo cerrado.
* Cancelado: Un ciclo de cultivo que se cancelo completamente. No se puede registrar movimientos, y sus movimientos han sido revertidos completamente.

#### 11.4.4 - Labor Agricola
La labor agricola es un comprobante de ejecución de una labor agendada por el ciclo de cultivo. También puede crearse
una labor agricola que no este agendada, pero que pertenezca a un ciclo de cultivo especifico.

Hay Varios tipos de labor agricola:

* Plantado / Transplantado (Movimiento de plantas)
* Irrigación (Agua)
* Fertilización
* Aplicación (Fertilización, Herbicida, Fungicida, Nematicida, Insecticida, Molusquicida, Pesticida, etc.)

### 11.5 - Configuración básica del Módulo de Agricultura
En esta sección usted aprendera como configurar su módulo agrícola con un simple cultivo
como la *Zanahoria*.

Se asume que usted ya realizó la configuración básica de ERPNext y que tiene una instancia
de ERPNext abierta en su ventana del navegador.


### 11.5.1 - Unidad de Cultivo
Antes que empecemos, necesitamos definir los detalles respecto a donde plantaremos nuestros
cultivos. Primero crearemos nuestra *Granja* como una **Unidad de Cultivo** madre, y luego 
agregaremos una o dos **Parcelas** como hijos o nodos, pertenecientes a la madre.

1. Haga clic en **Agricultura > Unidad de Cultivo**
2. Se desplegará un listado de las **Unidades de Cultivo** existentes.
3. Arriba a la derecha haga clic en **Nuevo**, para crear la primera **Unidad de Cultivo**
	3.1 Una Ventana de *ingreso rápido* se abrirá.
		3.1.1 Nombre de la **Unidad de Cultivo**: "Granja de Zanahoria"
		3.1.2 Madre de la **Unidad de Cultivo**: Vacío o "Todas las Unidades de Cultivo"
		3.1.3 Caja de Selección "Es Grupo": **Cheque** o **SI**
	3.2 Haga clic en ***Guardar**
	3.3 Con esto acaba de crear lo más importante: Una representación de su Granja en ERPNext.
4. Ahora, haga clic en la **Unidad de Cultivo** "Granja de Zanahoria" para poder agregar
	detalles.
	4.1 Abrirá el *Documento completo*
	4.2 Su navegador le solicitará permiso para *Compartir Ubicación* con ERPNext. 
		4.2.1 Si no esta en la granja al momento de crearla, ignore el permiso y usando el mapa
			o coordenadas geográficas, ingrese una ubicación.
		4.2.1 Si usted se ubica en la granja al momento de crearla, se sugiere que le de permiso.
		Con este permiso el mapa indicado en la **Unidad de Cultivo** estimará su ubicación para mostrarlo
	4.3 Si su granja requiere mayor detalle, por ejemplo, si usted cultiva en invernadero
		4.3.1 Haga clic en Caja de Selección "Es Grupo": **Cheque** o **SI**

## Modulo 12: Salud
### 12.1 - Configuración (Video 136)
### 12.2 - Paciente (Video 137)
### 12.3 - Cita de paciente (Video 138)
### 12.4 - Signos vitales (Video 139)
### 12.5 - Consulta (Video 140)
### 12.6 - Registro Médico del paciente (Video 141)
### 12.7 - Toma de muestras (Video 142)
### 12.8 - Prueba de laboratorio (Video 143)
### 12.9 - Facturacion (Video 144)
### 12.10 - Doctor (Video 145)
### 12.11 - Horario del doctor (Video 146)
### 12.12 - Estándares Legales Médicos (Video 147)

Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/healthcare)

## Modulo 13: Organizaciones Sin Fines de Lucro
### 13.1 - Membresía
### 13.2 - Capitulo
### 13.3 - Voluntario
### 13.4 - Donante
### 13.5 - Aplicación para solicitar fondos

Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/non_profit)

## Modulo 14: Hospitalidad
### 14.1 - Restaurant
### 14.2 - Menú de Restaurant
### 14.3 - Reservaciones de Restaurant
### 14.4 - Pedido de Restaurante
### 14.5 - Habitación de Hotel

Referir a [documentación original para verificar que nada falte](https://erpnext.org/docs/user/manual/en/hospitality)

## Modulo 15: Programando y Contribuyendo
### 15.1 - Aportando traducciones
#### 15.1.1 - Acceso al portal
#### 15.1.2 - Agregando idioma no listado
#### 15.1.3 - Acceso al portal
#### 15.1.4 - Distribuyendo el trabajo: Imprimiendo los mensajes en una hoja para entrevistas de campo
#### 15.1.5 - Anotando en una hoja en el campo, entrevistando a uno o dos parlantes nativos
### 15.2 - Aportando plan de cuentas regionalizados
#### 15.3 - Aportando ideas o sugerencias de mejora
#### 15.4 - Aportando informes de errores
### 15.5 - Desarrollando Aplicaciones
#### 15.5.1 - Antes de desarrollar 
	Revisa primero los forums para ver si hay ya un proyecto en curso que solucione el problema que tienes.
	Idealmente puedes participar de este proyecto.
#### 15.5.2 - Desarrollando aplicaciones [Original 1 ERPNext](https://youtu.be/TAz3CjO0VGY)
##### 15.5.2.1 - Como hacer una aplicación
##### 15.5.2.2 - Como usar GitHub
##### 15.5.2.3 - Creando una instancia de servidor de desarrollo desde cero con VirtualBox
* Estos pasos le guiarán para instala una máquina virtual con un servidor Linux .iso hasta que tenga un servidor ERPNext funcional para uso local
	* Estas instrucciones se basan en lo que ha servido para nosotros
	* Esta configuración   This setup is only recommended for a server that will be used locally!
###### 15.5.2.3.1 - Download and install VirtualBox
1. Visite https://www.virtualbox.org/
2. Clic en el botón azul grande para descargar: "Download Virtual Box 5.x"
3. Seleccione su sistema operativo y descaruge el archivo
4. Instale VirtualBox
5. Corra VirtualBox
###### 15.5.2.3.2 - Download Linux
Personalmente me gusta correr mis servidores de desarrollo en Linux Server. Quizás pueda querer usar [Ubuntu Desktop](http://releases.ubuntu.com/16.04/ubuntu-16.04.4-desktop-i386.iso.torrent).
Para prevenir temas de compatibilidad, recomiendo el [servidor de 32-bit Ubuntu 14.04 LTS](http://releases.ubuntu.com/16.04/ubuntu-16.04.4-server-i386.iso.torrent).
Visite la [Página de Ubuntu](https://www.ubuntu.com/download) para elegir la versión apropiada a sus necesidades.

También sugiero el uso de un administrador de torrentes, así obtendra descargas muy rápidas.
Personalmente utilizo [μTorrent](http://www.utorrent.com/)
y en una conexión de 10Mb logro descargarlo en menos de 15 minutos.

1. Vaya a la [Página de Ubuntu](https://www.ubuntu.com/download) y seleccione la versión adecuada a sus necesidades
2. Media vez ha seleccionado lo que necesita, haga click para bajar el archivo
3. La descarga sera un archivo de tipo **.torrent**
4. Si le hace doble clic o lo abre en su administrador de torrentes, lo agregará a la lista de torrentes
5. Asegúrese que ha iniciado el torrente y permita que comparta el archivo un tiempo después de finalizada la descarga
6. El resultado sera un archivo **.iso** que utilizará para preparar su servidor de desarrollo
##### 15.5.2.4 - Planificando su aplicación
##### 15.5.2.5 - Creando su aplicación
Antes de crear su app, abra [esta página](https://octicons.github.com/) en su navegador 
web y encuentre el nombre del icono que desea utilizar para su aplicación.

También necesita elegir un color para el cuadro de atrás del icono, puede ser:

Nombre estándar de HTML: **blue**
o
Valor de color en hexadecimal: **#000000**

Encuentre algunas ideas aquí: [https://www.w3schools.com/colors/colors_names.asp](https://www.w3schools.com/colors/colors_names.asp)

También necesita considerar que licencia utilizará para publicar su aplicación.
Anote la palabra clave para la licencia.

Algunas ideas aquí: [https://help.github.com/articles/licensing-a-repository/](https://help.github.com/articles/licensing-a-repository/)

Si ya tiene una instancia de ERPNext corriendo, también necesita el nombre del sitio de su instancia de ERPNext.

Desde la terminal o iTerm, en una conexión a su servidor con SSH o directamente:

1. Navegue al folder Frappe-Bench folder
	```cd /home/frappe/frappe-bench/```
2. Cree la aplicación
>```bench new-app [el_nombre_de_su_aplicación]```

Ejemplo:
> ```bench new-app mi-nueva-app```	

3. Se le pedirá:
	* Una linea simple con descripción de su aplicación
	* Quién publica el app (empresa, equipo, o persona)
	* Correo electrónico de quien publica el app
	* Icono de la aplicación: **octicon octicon-[name]**
	* Color del modulo de la aplicación: **#000000**
	* Licencia: **gpl-3.0**
4. Instale la aplicación a su sitio. Repita el comando para cualquier otro sitio en donde usted quiera la aplicación
> ```bench --site [nombre_del_sitio] install-app [el_nombre_de_su_aplicación] ```

Ejemplo:

> ```bench --site site1.local install-app mi-nueva-app```

* Nota: , la aplicación ya está instalada, pero no se mostrará el ícono en el escritorio o
	tampoco lo podrá encontrar allí. ¡Esto sucederá hasta que haya creado el primer DocType!

5. Cree su primer Tipo de Documento
	* Abra su navegador y escriba la dirección del servidor en donde tiene instalado ERPNext.
	* Haga Login
	* Media vez esta en el escritorio de ERPNext, haga clic en el *Awesome Bar* arriba y escriba:
	**new DocType**
	* Presione ENTER
	* Una página de configuración de nuevo DocType se abrirá
	* Sugiero que cree un DocType de configuración para su aplicación de primero.
		* En el campo *Is Single* seleccione **YES (SI)**
		* En el campo de *Name* (Nombre): **Configuration**
	* Clic en **Save** (Guardar)
* Nota: Si

6. Habilite modo desarrollador en la terminal

> ```cd /home/frappe/frappe-bench/sites/[your_site_name]```

Luego, abra el archivo site_config.json para agregar la linea de codigo que enciende el modo desarrollador:

> ```nano site_config.json```

Agregue la siguiente línea, justo después de **"db_password": "password_de_su_db"**,

> ```"developer_mode": 1,```

Ahora, salga, guarde y confirme: **CTRL + X, Y, ENTER**

7. Encuentre la aplicación en los directorios de linux:
Para modificar su aplicación, puede accesar el directorio en donde reside adentro del siguiente folder, y modificar los archivos

> ```cd /home/frappe/frappe-bench/apps/[el_nombre_de_su_aplicación]```

8. Opcional: Configure el folder de su aplicación para rastrear los cambios con GitHub
Media vez esté adentro del directorio, ejecuta los siguientes comandos:

> ```git init```

Lo confirmará, si tiene éxito, con :
**Initialized empty Git repository in /home/frappe/frappe-bench/apps/[el_nombre_de_su_aplicación]/.git/**

9. Agregue archivos al repositorio local de git
Esto agregará todos los archivos que tiene el el directorio, al repositorio git local:

> ```git add .```

10. Ahora, confirme sus cambios
Esto prepara los cambios y los coloca en el area de preparación de donde se empujarán los archivos.

> ```git commit -m "[Agregue un memo corto de su elección aquí]"```

11. Solo una vez: Si no lo  [ha hecho todavía](https://help.github.com/articles/create-a-repo/), vaya a su repositorio remoto en GitHub
	o cualquier otro servidor y haga clic en el link de copiar la dirección web del repositorio remoto, que está arriba a la derecha.
	
> ```git remote add origin [URL_que_usted_copió]```

Esto configurará el repositorio remoto por defecto a donde empujará y de donde jalará cambios.
Lo puede verificar con:
> ```git remote -v```

Debería obtener:
> origin  https://github.com/user/repo.git (fetch)

> origin  https://github.com/user/repo.git (push)

12. Finalmente, empuje sus cambios al repositorio remoto

**Importante: ¡El siguiente comando asume que el repositorio remoto está vacío!**
> ```git push -u origin master --force```

Para cualquier empuje en el futuro, solamente utilice:

> ```git push origin master```

##### 15.5.2.6 - Programando con Python
##### 15.5.2.7 - Programando con JavaScript
##### 15.5.2.8 - Modificando Archivos (Video 254)
##### 15.5.2.9  - Modificando Informes - Query report (ej. Agregar columnas) (Video 255)
##### 15.5.2.10 - Creando informes - Pages  (Ej. Sales Analytics, vs. Sales Analytics 2.0) (Video 258)
##### 15.5.2.11 - Creando Registros para que se incluyan en su aplicación
Muchas veces, la aplicación per se no necesita solamente de funcionalidad sofisticada sino que requiere de proporcionarle registros de utilidad para el usuario.  En ese caso podemos rescindir la utilidad de importar datos y simplemente incluirlos como por defecto al instalar la aplicación.

Mientras vaya desarrollando la aplicación, agregue los registros que necesite de la forma que desee.

Modifique su archivo `hooks.py` para que la variable `fixtures = []` contenga los DocTypes que usted desea.  Por ejemplo, aparte de los campos personalizados y scripts personalizados que existen en el ERPNext de desarrollo, deseo que como parte de la aplicación se incluyan los cuentas contables, los centros de costo y los grupos de artículos, entonces la linea debe de leer así:

Antes:
`fixtures = ["Custom Field", "Custom Script"]`

Después:
`fixtures = ["Custom Field", "Custom Script", "Account", "Cost Center", "Item Group"]`

Guarde el archivo.

Luego, ya con los registros como los desea, (y previo a hacer su commit y push al servidor git), ejecute el siguiente comando en su servidor de desarrollo:

cd /home/frappe/frappe-bench/ && bench export-fixtures

Este comando creará 5 archivos .json, uno para cada DocType, en el directorio `/home/frappe/frappe-bench/apps/[app-name]/[app-name]/fixtures/` de su aplicación, así:

custom_field.json
custom_script.json
account.json
cost_center.json
item_group.json

Estos archivos tendrán los registros que usted almacenó previamente, y al momento de instalar la aplicación en cualquier servidor, se cargarán automáticamente. El usuario no tendrá que cargarlos.
##### 15.5.2.12 - Haciendo pruebas
Ademas del ciclo usual de escribir codigo fuente > probar funcionalidad > fallar > probar funcionalidad de neuvo > triunfar, es necesario realizar pruebas de los scripts de python para asegurarse que el codigo fuente esta haciendo lo que supuestamente debe de hacer. Adentro del folder del DocType que esta creando, es imperativo crear por lo menos tres archivos
test_[nombre-del-doctype].py
test_[nombre-del-doctype].js
test_records.json

Los archivos Python y JavaScript contienen aseveraciones (assertions) que utilizan las funciones que usted programó, así como funciones locales y variables para confirmar explicitamente que la funcion del software hace exactamente lo que usted desea. Este proceso dramaticamente incrementa la integridad del software, y clarifica su funcionamiento para aquellos que lo estan evaluando o auditando el codigo fuente.
##### 15.5.2.13 - Creando Documentacion
##### 15.5.2.14 - Publicando su aplicación
##### 15.5.2.15 - Mantenimiento de su aplicación
#### 15.5.3 - Desarrollando sobre ERPNext
##### 15.5.3.1 - Como trabajar con GitHub sobre el repositorio principal
##### 15.5.3.2  - Solicitando un Pull Request

## Modulo 16: ERPNext Hub
## Modulo 17: Calendario y Contactos
## Modulo 18: Consolidación de cuentas para empresas matrices, hijas o hermanas
## Modulo 19: [*Reservado*] Aplicación propia SHS (Revelare)
Aplicación propia hecha por SHS en alfa (mayo 2018), con objetivo de contribuir al repositorio principal ERPNext
## Modulo 20: [*Reservado*] Aplicación propia SHS (GEV)
Aplicación propia hecha por SHS en alfa (mayo 2018), con objetivo de contribuir al repositorio principal ERPNext
## Modulo 21: [*Reservado*] Aplicación propia SHS (Facelec)
Aplicación propia hecha por SHS en version 2.1.1 (mayo 2018), con objetivo de contribuir al repositorio principal ERPNext
## Modulo 22: [*Reservado*] Aplicación propia SHS (Accesos Bancarios)
Aplicación propia hecha por SHS en fase de planificación. Regional. Objetivos:

* Acceso de records bancarios
* Programando pagos
* Autorizando Pagos
* Suplementando modulo de conciliación bancaria en ERPNext

## Modulo 23:  [*Reservado*]  Jalar tipo de cambio desde sitio Banguat
Este modulo obtiene el tipo de cambio publicado por el Banco de Guatemala y lo hace disponible en ERPNext, automáticamente.
## Modulo 24: Lo básico para ordenar y nombrar tus bodegas 
Basado en el [artículo](https://www.skuvault.com/blog/warehouse-locations-labeling-mistakes) de [Arianna Thayer](https://www.skuvault.com/blog/author/arianna-thayer)

### Como Ordenar sus bodegas (Almacenes)
Hablar del orden de su bodega puede ser algo aburrido, puesto que tiene otras cosas más importantes
que hacer. ¿Para que ordenarlas adecuadamente?

* Reducir tiempo en buscar, obtener y utilizar insumos
* Minimizar los errores
* Minimizar desperdicios
* Cumplir con normativas de certificaciones

La combinación de esto evidentemente resulta en una reducción de costos y mejores ventas,
 los cuales se trasladan directamente a su operación. Una bodega ordenada hace las tareas más faciles, rápidas y efectivas.
 Cumplir ocn una certificación ayuda en abrir más mercados.

Entonces, si desea mejorar su operación partamos desde los estándares aceptados para manejo de bodegas.
Estos estándares surgieron despues de muchas pruebas y errores en otras organizaciones a lo largo del tiempo.
Conforme el paso del tiempo, se ha llegado a un común acuerdo desde lo informal hasta una formalidad, a lo cual
se le llama *Estándar de la industria*. Aqui veremos los concéptos básicos que puede aplicar para
tener excelentes resultados desde el inicio.

Al administrar las ubicaciones de las bodegas adecuadamente, se podrá utilizar herramientas y sistemas
comúnmente utilizados como: obtención interactiva de objetos por fase ó ubicaciónes dinámicas.

Obtencion Interactiva de Objetos por Fase (OIOF): Interactive Wave Picking, le permite a la persona encargada
de obtener objetos en bodega, de hacer su ruta eficiente, desglosando el total de articulos que recogerá
en una sola lista que asegura que solo recorra una vez cada pasillo o estantería.  Si tengo 5 pedidos
con un total de 20 objetos, algunos de ellos repetidos, el sistema OIOF me desplegará la lista de tal manera que
pase recogiendo cantidades de objetos a obtener, para cuando retorne a mi punto de partida, ya los asigne a
los pedidos correspondientes.

https://www.skuvault.com/features/interactive-wavepicking.php
https://en.wikipedia.org/wiki/Wave_picking
https://www.skuvault.com/features
https://en.wikipedia.org/wiki/Warehouse_management_system

Ubicaciónes dinámicas: En un sistema de ubicación dinámica, se permite que la ubicación de los productos
cambie de posición en las ubicaciones de bodega. Un ejemplo de esto es que los productos más
comunes puedan ser almacenados mas cercanos a la ubicación donde se empacan o utilizan.

http://microchannel.com.au/company-blog/march-2015/warehouse-management-static-vs-dynamic-slotting
https://www.youtube.com/watch?v=31GfSd0oIzg

Ambas estructuras mencionadas arriba le permiten reducir el tiempo de obtención de los objetos.

### Terminología
Previo a sugerirle como nombrar sus bodegas, clarifiquemos la terminología.

**Ubicación**: (En inglés: **Location**) Un area designada y etiquetada en su bodega, en donde una persona va a obtener los objetos
para un pedido. Típicamente se identifica con una serie de codigos alfanuméricos (que pueden incluir codificacion en barra) que pueden usarse
para rápidamente registrar la salida o ingreso de un producto en sus sitema de administración de bodega (almacén).

**Pasillo**: (En inglés: **Aisle**) La siguiente forma de indicar ubicación es por **Pasillo**, el cual se
define como el espacio entre sus **Estanterías** por el cual se puede mover usted o su maquinaria de bodega (Montacargas, etc.)

**Estantería**: (En inglés: **Rack**, **Unit**, o **Sección**) Se refiere a la seccion de unidades o modulos
que contienen Entrepaños para almacenar los productos. Dependiendo de la bodega, las **Estanterías** se pueden identificar
como una unidad entera a lo largo de un **Pasillo**, o como secciones de **Entrepaños** largos. Se puede imaginar
lo descrito como un montón de libreras alineadas en una fila, con cada librera en su propia **Estantería** dentro de
la fila de **Estanterías**.

**Entrepaño**: (En inglés: **Shelf**) El siguiente nivel de ubicación a la cual se le coloca nombre es el **Entrepaño** o **Fila**.
Este es el espacio horizontal que atraviesa la enteridad de la Estantería en donde se ubica.

**División**: (En inglés: **Division or Subdivision**) Esto divide su entrepaño en unidades lógicas que permiten separar objetos más pequeños
Si el objeto ocupa toda la estantería, entonces no es necesario utilizar esta numeración.

**Recipiente**: (En inglés: **Bin**) Es cualquier tipo de almacenamiento *adentro* de uno o mas espacios o divisiones para
el producto almacenado. (Por ejemplo: Un recipiente de clavos, otro de tornillos, etc.). Esta es la ubicación mas específica
que se sugiere utilizar en una bodega. Ocasionalmente se puede intercambiar con el término **Ubicación**.

Si deseamos ver una jerarquía de su bodega, lo lógico es entonces definirla de lo general a lo específico como:
#### Ubicación General > Grupo de Bodegas > Bodega > Pasillo > Estantería > Entrepaño > División > Recipiente

### Como Nombrar sus bodegas (Almacenes)
Para nombrar su bodega, asegúrese de elejir algo que le funcione, y sea consistente en el esquema que elijió.

Las mejores prácticas para nombrar sus bodegas es la siguiente:

1. Numere los **Entrepaños** del suelo hacia arriba. De esta forma, si necesita agregar 
	entrepaños, no tiene que volver a etiquetarlos. Por ejemplo, si tiene una **Estantería**
	con cuatro **Entrepaños**, siendo el superior etiquetado como **#1**, y el de hasta abajo como
	el **#4**, si desea agregar ubicaciones (**Entrepaños**), su nueva ubicación (supongamos 
	que es el **Entrepaño #5**) quedaría encima del **Entrepaño #1**. Evidentemente esto le complica todo.
2. Es recomendable que cuando desee utilizar numeración en las ubicaciones, utilice un 
	cero en todos los numeros inferiores a diez (Por Ejemplo: 01, 02, 03, etc.).  Esto le permite a su
	sistema leer las ubicaciones alfanuméricas codificadas en código de barras, correctamente. 
	Además, le simplifica la lectura a su personal, puesto que se acostumbran a leer dos dígitos siempre.
3. Sea consistente. Un sistema inconsistente de etiquetado le herá más dificil el trabajo a sus empleados.

Debido a que la variedad de productos que se almacenan es muy cambiante, en algunos casos se necesita
mucho detalle, y en otros se necesita menos detalle (Ej. Bodega que almacena neumáticos 
de vehiculo versus una que almacena componentes para computadoras)

#### Dos formas

##### Serpentina
Los expertos sugieren siempre un almacén estructurado como serpentina, el cual permite a su personal
recorrer en forma de culebra o "S" hacia adentro y afuera de los pasillos para dejar o recoger los productos necesarios.
Esto permite que su personal no recorra mas de dos veces cada pasillo para ingresar al otro pasillo. En casos
donde se utiliza la metodología de *Obtencion Interactiva de Objetos por Fase (OIOF)*, reduce el tiempo necesario
para obtener todos aquellos objetos que permiten cumplir con los productos requeridos.

La estructura se vería así:
![Estanteria-FS-Serpentina](/activos/imagenes/Estanteria-FS-serpentina.png)

##### Estándar
Un método estándar estructura su almacén similar a la serpentina, solo que todas las estanterías o grupos de estanterías
inician desde el mismo pasillo cruzado. Con esto, se debe retornar al inicio del pasillo para contar estanterías
hacia arriba.

### Como Nombrar los recipientes en sus Entrepaños
Media vez hemos ubicado adentro de la bodega o almacén, y hemos llegado al entrepaño que contiene
los objetos deseados, todavía nos queda navegar cualquier potencial división del entrepaño.
Para este efecto, nos queda solamente etiquetar por sección o división lógica.

La mejor forma de hacer esto es mediante la colocación en cada **Entrepaño** de **Recipientes** enumerados
horizontalmente (de izquierda a derecha). Cada serie numerada debe de llegar hasta el final del entrepaño.
Es importante anteponerle una letra **"D"** (**Division**) previo al numero,
y utilizar el esquema de dos digitos: D01, D02, D03, etc.
Esto logra diferenciar claramente el numero de **Division** de la numeración que identifica al **Pasillo** y **Estantería**.

Si los objetos que deseo buscar se encuentran en la ubicacion **02-BE-04** y a ese entrepaño lo subdividimos en 4
ubicaciones adicionales, cada una de esas cuatro ubicaciones serán:
**02-BE-04-D01**
**02-BE-04-D02**
**02-BE-04-D03**
**02-BE-04-D04**

La estructura se vería así:

### Más específico: Organizadores adentro de los recipientes
Supongamos que usted desea ubicar objetos más pequeños, los cuales únicamente los coloca
en **Gavetas** pequeñas. Ejemplos de estos pueden ser distintos tamaños y tipos tornillos, tuercas, roldanas, clavos, etc.
Usted puede colocar **Organizadores** de tipo cubeta cuadrados apilables, o **Cajas organizadoras con gavetas pequeñas** para continuar
subdividiendo el espacio del entrepaño en espacios lógicos. Cada uno de estos es un **Recipiente**.

Supongamos que a la ubicación del ejemplo anterior:  **02-BE-04-D01**
Le colocamos 5 **Recipientes** (Conocidos como: Cajas organizadoras o "Bins" en inglés) verticalmente, podemos enumerar de abajo para arriba como:
**R01**, R02, R03, R04, R05.  Si deseamos ubicar algo que está en el primer **Recipiente**, la ubicación es entonces:

**02-BE-04-D01-R01**

En el caso de las **Cajas organizadoras con gavetas pequeñas**, no se sugiere subdividir por columna y fila, sino 
simplemente enumerar. Si una **Caja organizadora con gavetas pequeñas** posee 5 niveles y 10 columnas para
un total de 50 gavetas, cada gaveta se considera un recipiente y se sigue contando hasta 50. 
Por ejemplo, si deseamos ubicar algo en la gaveta 49, el código es:

**02-BE-04-D01-R49**














# ESTE DOCUMENTO ES TRABAJO EN PROCESO!