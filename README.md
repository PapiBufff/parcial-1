# parcial-1
el código que se  desarrollo en compañía de LicWalter, es sobre un sistema de gestión del inventario.
Desarrolla un programa que implemente un arreglo tipo FIFO (First In, First Out) para gestionar el inventario y las ventas de productos de un almacén.

Cada producto en el inventario debe registrarse con la siguiente información:

ID del producto: un número entero único para cada producto.
Nombre del producto: una cadena de caracteres.
Cantidad: un número entero que representa la cantidad de unidades disponibles del producto.
Precio por unidad: un valor decimal que representa el costo de cada unidad del producto.
El programa debe ser capaz de realizar las siguientes operaciones:

Registrar Producto: Agregar un nuevo producto al final de la cola del inventario. (+10 Puntos)
Mostrar Inventario: Listar todos los productos en el inventario, mostrando su ID, nombre, cantidad y precio por unidad. (+10 Puntos)
Buscar Producto por ID: Buscar y mostrar la información de un producto utilizando su ID. (+10 Puntos)
Eliminar Producto: Eliminar un producto del inventario basado en su ID. Esta operación debe remover el primer producto que coincida con el ID proporcionado. (+20 Puntos)
Calcular el Valor Total del Inventario: Sumar el valor total de todos los productos en el inventario (Cantidad * Precio por unidad) y mostrar el resultado. (+10 Puntos)
Calcular el Promedio de Precios: Determinar el precio promedio por unidad de todos los productos en el inventario. (+10 Puntos)
Vender Productos: Permitir la venta de productos mediante el siguiente proceso:

Solicitar al usuario el ID del producto a vender.
Buscar el producto por su ID y mostrar su información.
Preguntar al usuario la cantidad de unidades que desea comprar. 
Verificar si hay existencias suficientes del producto. Si no hay suficientes, informar al usuario y cancelar la venta.(+10 Puntos)
Si hay existencias suficientes, descontar la cantidad vendida del inventario y calcular el total a pagar (Cantidad * Precio por unidad). (+10 Puntos)
Mostrar al usuario el total a pagar por los productos vendidos. (+10 Puntos)
