# Cafe Aroma
Proyecto ABP 
# Introducción 
Bienvenidos a nuestro pequeño cafeteria Cafe Aroma, nuestra vision nace con la pasión por ofrecer una experiencia única a todos los amantes del buen café, nos enfocamos en seleccionar granos de alta calidad, cultivados de manera sostenible y con prácticas de comercio justo. Buscamos no solo brindar una taza excepcional, sino también educar a nuestros clientes sobre el proceso que hay detrás de cada grano, desde la cosecha hasta la taza. Además, ofrecemos una variedad de preparaciones para todos los gustos, creando un espacio donde cada sorbo sea una invitación a disfrutar del arte del café en su máxima expresión.
# Análisis de requerimiento 
Mi emprendimiento de venta de café requiere un espacio acogedor donde los clientes puedan disfrutar de una excelente taza de café, ya sea en una cafetería física o a través de una tienda en línea. Contamos con equipos de alta calidad, como molinillos y máquinas de espresso, y trabajamos con proveedores que ofrecen granos premium, garantizando un producto fresco y delicioso. Además, nos aseguramos de tener todo en regla con los permisos y licencias necesarios para operar legalmente y brindar un servicio seguro.

Para atraer a nuestros clientes, hemos creado una estrategia de marketing que incluye promociones y presencia en redes sociales, buscando siempre conectar de manera auténtica con los amantes del café. La gestión financiera es clave para mantener el negocio en marcha, controlando los costos y asegurando la rentabilidad. También nos importa el medio ambiente, por lo que usamos empaques biodegradables y buscamos ser cada vez más sostenibles en todos nuestros procesos. Todo esto con el objetivo de ofrecer una experiencia única y memorable a cada cliente que elija nuestro café.
# Modelo Relacional 
![image](https://github.com/user-attachments/assets/f18e70e8-580a-44dd-b44c-67431f024e29)

Resumen y descripcion de las tablas:

Productos: Guarda la información del café disponible para la venta, como el nombre, precio, stock, y categoría.

Clientes: Contiene los datos de los clientes, para asociar ventas a personas específicas.

Empleados: Información sobre los empleados que realizan las ventas.

Ventas: Contiene las transacciones realizadas, asociando a un cliente y un empleado. Se puede ver el total de cada venta.

Detalles de Venta: Detalles específicos sobre los productos vendidos en cada transacción (productos, cantidades y precio).

Proveedores: Si necesitas controlar los proveedores del café.

Compras de Café: Registra las compras realizadas a los proveedores para actualizar el stock.

Detalles de Compra: Detalles específicos de los productos comprados.

