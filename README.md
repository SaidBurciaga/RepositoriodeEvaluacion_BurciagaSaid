# RepositoriodeEvaluacion_BurciagaSaid

Actividad 2,17

Said Antonio Burciaga Parada

En este repositorio estara la practica 2.16 con el que se creara una array asociativo en el cual saldra el nombre del empleado con su sueldo mensual

Código: 

<!DOCTYPE html>

<html>
	
<head>
	
	<title>Actividad 2.16</title>
 
		<style type="text/css">
		body{
		background-color: lightyellow;
			font-family: sans-serif;
   
			font-size: 35px;
   
			text-align: center;
		}
	</style>
 
</head>

<body>
	<?php
	
	//Realiza una arreglo de  5 empleados y su sueldo mensual,ordena el arreglo,imprime ,Agrega 2 empleados mas con su sueldo, con la instrucción  array_push(),imprime.
 
$empleado = array("Juan"=>"5000", "Carlos"=>"4500","Angel"=>"9000","Yael"=>"6000","Said" => "20000");

arsort($empleado);

foreach ($empleado as $nombre => $salario) {
	echo $nombre." gana al mes ".$salario;
	echo "<br>";
}

echo "<p>";


$empleado ["Cristofer"]= "7000";

$empleado ["Alex"]="10000";

arsort($empleado);

foreach ($empleado as $nombre => $salario) {
	echo $nombre." gana al mes ".$salario;
	echo "<br>";
}

?>

</body>

</html>
