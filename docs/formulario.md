# Input Radio y Checkbox

# Radio (Radio Button)
-Usamos radio cuando tenemos un conjunto de opciones 
y solo queremos que el usuario escoja 1
* Plan de pagos (Netflix) => 3 planes y solo que el usuario tenga 1
* Plan de celular => solo quiere que tengas 1 
* Curso junior - Intermedio - Avanzado

## Checkbox
* Usamos checkbox cuando queremos que el usuario marque mas de una opcion
*Netflix (Cuando entremos por primera y nos permite seleccionar multiples generos de pelicula o series)
* Lista de mercado (Marcamos las opciones que compramos)
* Compra de un carro (Escoger y marcar las opciones del carro)

## checked 
- Permite que mi chekbox o radio esten marcados por defeceto

## readonly vs disabled

## readonly
- Se usa cuando queremos hacer un input no sea editable, pero queremos mantener su valor al momento 
de enviar la información

## disabled
-Se usa cuando queremos hacer que un input no sea edtiable, pero esto no se conserva el valor

* porque al momento de enviar la informacion, sabemos que enviamos el valor de cada input,
pero si el input tiene la propiedad *disabled* este valor sera nulo, sin embargo si usa *readonly*
el valor sera enviado