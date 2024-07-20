# pedidos_mesa
Este es el servicio de autenticación de un software para hacer los pedidos de la clientela en un restaurante


### Tabla de contenido

#### Funcionamiento
#### Modelo de datos
#### Tecnologías
#### Modo de uso
#### Elaborado por


### Funcionamiento

Este software consta de una página de login y una página principal de saludo
Debe ingresar con el usuario y contraseña que se encuentran guardados en una base de datos MySQL


### Modelo de datos

![Modelo de datos](modeloDatos.png?raw=true)

### Tecnologías

- Python 3
- Framework flask

### Modo de uso
En la tabla flask_login debe estar guardado el username y el password que posteriormente la herramienta va a ir a comparar con el que digita el o la usuaria

![login](login.png?raw=true)

Si es correcto tanto el login como el password lo dirigirá a una nueva ventana que contiene el mensaje 'Bienvenid@ "Escribe el nombre de la persona logueada" '

Si es incorrecto entonces saldrá un mensaje donde dirá "Invalid Username or password..."

### Elaborado por:

Nombre: Marcia Castro Moya

Email: marcas4@gmail.com

X: @marcas4


