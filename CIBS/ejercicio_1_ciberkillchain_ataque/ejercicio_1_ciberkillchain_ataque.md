# Ejercicio CiberKillChain - Ataque

## Alumno

Fabián Alejandro Banderas Benítez

## Enunciado

Armar una cyberkillchain usando técnicas de la matriz de Att&ck para un escenario relacionado al trabajo práctico de la carrera.

### Datos del trabajo práctico
#### [Link](https://github.com/fabianbanderasb/Plantilla-planificacion/blob/changes/charter.pdf)
#### Descripción técnica-conceptual del proyecto a realizar

Debido a la incursión de medios Smartphone, dispositivos electrónicos que se conectan a través de internet, es necesario dar una solución más sencilla para mostrar reportes de registro de entrada y salida del personal que labora en el interior de la empresa. ``En la Figura se presenta el diagrama en bloques del sistema. Se observa que desde el dispositivo se hace el registro, este se procesa, valida, asigna de forma interna para luego enviar la notificación respectiva a quien corresponda.

A falta de un registro de entrada y salida con notificaciones para crear una mejor distribución de tiempos entre empleados se presenta la propuesta que consta de:

- Supervisor
- Empleados
- Destinatarios para recibir notificación
- Registros

Los dispositivos a través los cuales se generan los registros, se conectarán para enviar los datos e intercambiarlos con los diferentes dispositivos. Los requerimientos mínimos se muestran a continuación:

- La aplicación permite la autenticación de los miembros registrados.
- El empleado hará el registro de ingreso.
- El supervisor y personal recibirá la notificación push de ingreso.
- El cambio de estado y el tiempo de estancia empezará.
- El empleado hará el registro de salida.
- El supervisor y personal recibirá la notificación push de salida.
- Las métricas de cada uno de los empleados deben ser visuales a través de grafos.

![Imagen](https://github.com/fabianbanderasb/Plantilla-planificacion/blob/changes/Figuras/diagBloques.png)


## Resolución
### Metodología: Cyberkillchain

### Objetivo del ataque: 
Extraer los datos privados del personal que se autentica en la aplicación de registro de entrada y salida.
### 1.- Reconnaissance(Reconocimiento)
  
![Attack](https://attack.mitre.org/techniques/T1589/)
El atacante recopila información sobre la aplicación de registro de entrada y salida, como su arquitectura, tecnologías utilizadas, posibles vulnerabilidades y los empleados que la utilizan.
### 2.- Weaponization(Arma)
  
El atacante desarrolla el malware o la herramienta necesaria para explotar las vulnerabilidades identificadas en la aplicación y extraer los datos de registro de entrada y salida.
### 3.- Delivery(Entrega)
  
El atacante entrega el malware o la herramienta al dispositivo de un empleado a través de medios como la descarga de una aplicación falsa o el engaño mediante técnicas de ingeniería social.
### 4.- Exploit(Explotación)
  
El malware o la herramienta explota las vulnerabilidades de la aplicación para obtener acceso no autorizado y extraer los datos de registro de entrada y salida del personal.
### 5.- Installation(Instalación)
  
![Attack](https://attack.mitre.org/techniques/T1021/)
Una vez que el malware ha explotado con éxito las vulnerabilidades, se instala en el dispositivo del empleado y establece una presencia persistente para continuar recopilando los datos de registro.
### 6.- Command & Control(Comando y control)
  
El malware establece una comunicación con el servidor controlado por el atacante para transmitir los datos de registro extraídos del dispositivo del empleado.
### 7.- Actions on Objectives(Acciones sobre los objetivos)
  
El atacante utiliza los datos de registro de entrada y salida para su propio beneficio, como obtener información sobre los horarios de los empleados y crear una otra distribución de tiempos entre ellos.
