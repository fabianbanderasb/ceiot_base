# Ejercicio CiberKillChain - Defensa

Hacer una copia de este documento para utilizar com plantilla para el ejercicio

## Alumno

Fabián Alejandro Banderas Benítez

## Enunciado

Desarrollar la defensa en función del ataque planteado en orden inverso.

Para cada etapa elegir una sola defensa, la más importante, considerar recursos limitados.

## Resolución

### 7.- Actions on Objectives(Acciones sobre los objetivos), 6.- Command & Control(Comando y control), 5.- Installation(Instalación)
  

* [Technique](https://attack.mitre.org/techniques/T1098/) Account Manipulation
* [Sub-Technique](https://attack.mitre.org/techniques/T1098/005/) Account Manipulation: Device Registration

* [Technique](https://attack.mitre.org/mitigations/M1043/)Credential Access Protection

Los dispositivos se pueden registrar en un sistema de autenticación multifactor, que gestiona la autenticación en la red, o en un sistema de
 gestión de dispositivos, que gestiona el acceso y el cumplimiento de los dispositivos.

Definir direcciones estáticas para en dispositivos móviles de la empresa y los dispositivos que se usan para el registro de multifacotor.

### 4.- Exploit(Explotación)
  
* [Technique](https://attack.mitre.org/mitigations/M1036/) Account Use Policies
 
Personalizar las opciones vinculadas al empleo de las cuentas de los miembro de la empresa SER&PROa, como medidas para prevenir accesos
 no autorizados, restricciones horarias de inicio de sesión, entre otros.

### 3.- Delivery(Entrega), 2.- Weaponization(Arma), 1.- Reconnaissance(Reconocimiento)

  
* [Technique](https://attack.mitre.org/mitigations/M1017/) User Training 

Proporcionar instrucción a los usuarios para que sean conscientes de los esfuerzos de acceso o manipulación realizados por personas
 malintencionadas, con el objetivo de disminuir la posibilidad de caer en tácticas de phishing, ingeniería social y otros métodos
 exitosos que implican la participación del usuario.

### Metodología: Cyberkillchain invertida

### Objetivo de la defensa: 
Evitar la exposición de datos los datos privados del personal que se autentica en la aplicación de registro de entrada y salida de la base de
 datos.
