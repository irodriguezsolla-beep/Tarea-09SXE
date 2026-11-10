# 1 Bases de datos: Captura del gestor con demo y primo, e idioma y país con que se crearon.
![Tarea91.png](Fotos/Tarea91.png)
![Tarea92.png](Fotos/Tarea92.png)
![BasesCreadas.png](Fotos/BasesCreadas.png)

EJERCICIO 1. TIPOS DE PRODUCTO localiza en demo un producto de cada tipo, fíjate en si
tiene impuestos asignados y haz una captura de su ficha

Los que tiene la estrellita son los que seleccione.
No tenian impuesto asiginados asi que se los asigne yo a los 2 que me dejo.
![productosdecadatipo.png](Fotos/productosdecadatipo.png)
![AlojamientoHotel.png](Fotos/AlojamientoHotel.png)
![Setoficina.png](Fotos/Setoficina.png)
![Sofa.png](Fotos/Sofa.png)

EJERCICIO 2. RECORRIDO. Haz este recorrido y guarda una captura de cada paso para el
README.
- 1. Contactos: abre un contacto de empresa y uno de persona. Fíjate en la diferencia entre Compañía e Individuo y en cómo las personas quedan vinculadas a su empresa.
Empresa
![Contactoempresa.png](Fotos/Contactoempresa.png)
Individuo
![Contacto individuo.png](Fotos/Contacto%20individuo.png)

- 2. Contactos: crea un cliente nuevo con su CIF y dirección, y asígnale una etiqueta.
![DAnielcastelao.png](Fotos/DAnielcastelao.png)

- 3. Productos: crea un servicio Hora de soporte a 40 € con Impuesto de ventas del 21 % y un bien Libro técnico a 25 € con el 4 %. Marca Ventas en los dos.
Hora de soporte
![Hora de soporte.png](Fotos/Hora%20de%20soporte.png)
![PrecioHora.png](Fotos/PrecioHora.png)
Libro técnico
![Libro técnico.png](Fotos/Libro%20t%C3%A9cnico.png)
![precioLibro.png](Fotos/precioLibro.png)
- 4. Ventas: crea un presupuesto para ese cliente con esos dos productos, envíalo (sin correo real), confírmalo y fíjate en que pasa a ser pedido de venta 
![Crearpresupuesto.png](Fotos/Crearpresupuesto.png)
![Presupuestocreado.png](Fotos/Presupuestocreado.png)
![ConfiguraciónDelafactura.png](Fotos/Configuraci%C3%B3nDelafactura.png)
![Configuracion del coreo automatico.png](Fotos/Configuracion%20del%20coreo%20automatico.png)
- 5. Facturación: desde el pedido, crea la factura y comprueba que cada línea lleva su IVA y que el total cuadra. Confírmala, imprímela en PDF y registra el pago. Comprueba la etiqueta Pagado.
![Factura.png](Fotos/Factura.png)

- 6. Facturación: localiza una factura de proveedor de los datos de demostración y compara sus campos con una de cliente.
Factura Proveedor
![FActuraproveedor.png](Fotos/FActuraproveedor.png)
Factura Cliente
![facturacliente.png](Fotos/facturacliente.png)
- 7. Chatter: en la parte derecha o inferior de cualquier registro está el historial de cambios, mensajes y actividades. Programa una actividad (una llamada) para
Programar llamda
![Programarllamada.png](Fotos/Programarllamada.png)
Llamada programada
![LlamadaProgramada.png](Fotos/LlamadaProgramada.png)

EJERCICIO 3. BÚSQUEDA GUARDADA. en Facturación → Clientes → Facturas, muestra solo las facturas publicadas, agrupadas por cliente, en vista lista, y guárdalo como favorito. Haz una captura.
![favoritos.png](Fotos/favoritos.png)
![filtros.png](Fotos/filtros.png)

EJERCICIO 4. MODO DESARROLLADOR Con el modo desarrollador activo, averigua el nombre técnico de dos campos del formulario de contacto y el modelo de una factura
![Activar el modo desalollador.png](Fotos/Activar%20el%20modo%20desalollador.png)

Se me olvido poner la foto conforme entro en modo desarrollado del siguiente modo http://localhost:8069/odoo?debug=1.

Nombre técnico de dos campos del formulario de contacto 
![Captura desde 2026-11-10 10-33-01.png](Fotos/Captura%20desde%202026-11-10%2010-33-01.png)
![Captura desde 2026-11-10 10-33-16.png](Fotos/Captura%20desde%202026-11-10%2010-33-16.png)

| campo     | nombre técnico | modelo      | 
|:----------|:---------------|:------------|
| NIF       | val            | res.partner |
| Sitio Web | website        | res.partner |

Modelo de una factura
![Captura desde 2026-11-10 11-01-32.png](Fotos/Captura%20desde%202026-11-10%2011-01-32.png)
![Captura desde 2026-11-10 11-01-36.png](Fotos/Captura%20desde%202026-11-10%2011-01-36.png)

| campo                | nombre técnico   | modelo       |
|:---------------------|:-----------------|:-------------|
| Fecha de factura     | invoice_date     | account.move |
| Fecha de vencimiento | invoice_date_due | account.move   |


Incidencias:

| Fecha                | Síntoma                                                                                            | Causa                               | Solución                             |
|:---------------------|:---------------------------------------------------------------------------------------------------|:------------------------------------|:-------------------------------------|
| 10/11/2026           | En la pestaña de productos, los productos aparecen en dolares en vez de €                          | No encontrada                       | No encontraada                       |
| 10/11/2026           | En la parte de filtrados de facturas, se pide filtrar por facturas publicas y no existe ese filtro | En la explicacion  pone publicadas  | El filtro en realidad era registrada |


Uso de la IA:
Use la ia para Intentar solucionar las dos anteriores Incidencias, me soluciono una, pero la otra no fue capaz.
