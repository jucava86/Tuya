# Tuya

Se debe crear la base de datos con la información que se encuentra en el archivo script.
Se debe usar la función /api/User/login enviando com
Y enviar por post 
{
  "usuario": "jucava86",
  "password": "string"
}
Para obtener el token ya que se usa Bearer  para realizar la validación


Para agregar registros a la base de datos se ejecuta la función /api/Productos/CargueInicial


Se pueden agregar, listar, editar y el eliminar (CRUD) categorías, productos, ventas y facturas en los diferentes servicios  