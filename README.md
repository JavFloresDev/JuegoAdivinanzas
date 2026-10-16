# Calculadora Básica de Consola

Juego de Adivinanzas de palabras en Java que funciona por ventanas graficas. Para dos usuarios donde usuario_1 ingresa una palabra y al iniciar el usuario_2 debe encontrar la palabra por medio del ingreso de letras hasta completarla.

## Características

- Conteo de intentos, fallos y aciertos del usuario
- Barra de progreso que incrementa con los fallos
- Fallos permitidos: 5 max
- Bucle si se desea reiniciar el Juego
- Opción clara para salir

## Requisitos

- Java 11 o superior

## Tecnologías utilizadas

- Java
- Java JFrame

## Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/JavFloresDev/JuegoAdivinanzas
```
2. Entrar a la carpeta del proyecto:
```bash
cd JuegoAdivinanzas
```
3. Compila el programa:
```bash
javac --release 11 src/juego/NewJFrame.java
```
4. Ejecuta el programa: 
```bash
java -cp src/juego 
```

## Ejemplo de uso
```
=== Calculadora Básica ===
Operaciones disponibles: +  -  *  /
Escribe 'salir' para terminar.

Primer número: 25
Segundo número: 5
Operación (+, -, *, /): /
Resultado: 5.0

Primer número: 10
Segundo número: 0
Operación (+, -, *, /): /
Error: No se puede dividir por cero.

Primer número: 0 : 0
¡Hasta luego!
```

## Estructura del proyecto

```
calculadora-basica-java/
├── src/
│   └── Calculadora.java
├── README.md
└── LICENSE
```

## Capturas de pantalla

![Calculadora en funcionamiento](images/calculadora.png)

## Autor

JavFloresDev — Jhonny Flores

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE [blocked] para más detalles.
