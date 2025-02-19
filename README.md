Siguiendo la arquitectura propuesta en clase crear una endpoint que se llame estacionamiento/agregar.php  que reciba el siguiente json. 
{ 
"PatenteVehiculo": "AC878FE", 
"TipoVehiculo": "Auto", 
"UsuarioAlta": "pedro" 
}
Y debe responder un JSON similar al siguiente:
{
 "IsOk":true,
 "Mensaje": "[Tipo vehiculo no existe | Ok]" 
}
El mensaje puede ser “Tipo vehículo no existe ” o “Ok” dependiendo de la TipoVehiculo.
Si TipoVehiculo ==  “Auto” o TipoVehiculo ==  “Moto” o TipoVehiculo ==  “Pickup” mostramos como Mensaje “OK”
En otro caso mostramos como Mensaje “Tipo vehículo no existe”
