# P10-Servo

# P8-Humedad

## (CC-BY-NC-SA) Adrián Cobo Merino

El objetivo de este esta práctica es tener la primera toma de contacto con el servo.

Para el ejercicio 1, hemos incluido 4 marchas(1,2,3,4). Al introducir '1' o '3' o 'w', el servo irá hacia un sentido pero a una velocidad
baja, media o alta respectivamente, y si se introdujese '2' o '4' o 's', haría lo mismo pero en el sentido contrario.

Para el ejercicio 2, simplemente hemos añadido un método que al calcular la velocidad lineal para el máximo PWM,hace una regla de 3 para 
obtener la velocidad lineal del pwm que respecte al metodo que esté haciendo al servo que se mueva o pare y que imprima dicha velocidad
por pantalla.

**Importante**
Para que dichos programas funcionen, hay que arrancar el demonio pigpiod y ejecutar los programas por terminal. Para ello escribe en un
terminal:

	sudo pigpiod
	python3 nombredelprograma	
	
**El esquema de conexión es igual que el facilitado en el enunciado a diferencia de que se ha cambiado el pin 14 por el pin 16**

Si quieres ver un video de demostración del ejercicio 1, pulsa [aqui](https://drive.google.com/file/d/12ce3sEAWTCcvAty007slsAjbdfLDumAh/view?usp=sharing).
Si quieres ver un video de demostración del ejercicio 2, pulsa [aqui](https://drive.google.com/file/d/1lZsmyKky0ohxxjqco_X5MCmbGADyzrtE/view?usp=sharing).


Para cualquier duda: <a.cobo.2020@alumos.urjc.es>
