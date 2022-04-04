# Companion Buddy
**Project manager:** A definir
**Ultima revisión:** 4 de abril del 2022
**Matería:** Laboratorio IV
**Integrantes:** 
- Darré, Juan Cruz
- de Aragón, Juan Manuel
- Godoy, Matias

### Propósito del proyecto: 
> El propósito de este proyecto es desarrollar un software que permita automatizar tareas en la plataforma [MiUbp3](https://miubp3.ubp.edu.ar/main)
### Objetivos del proyecto: 
>Se pretende interpretar comandos de voz realizados por el usuario, y mediante la automatización interactuar con la plataforma realizando la tarea previamente solicitada por el operador.
### ¿Cómo funciona?
_Para saber cómo funciona primero vamos a plantear el diagrama del funcionamiento a gran escala, el mismo se va a dividir en tres bloques._
- El primer paso es interpretar la expresión del usuario, la idea es hacerlo mediante un módulo de Python llamado SpeechToText (Impulsado por Google).
- Ya teniendo la expresión del usuario vamos a interpretar la misma y traducirla a un comando comprensible por nuestro sistema. 
- Esto desatará una acción por parte de selenium* lo cual mediante automatización nos permitirá interactuar con la pagina web (completando la tarea solicitada por el usuario).
*tal véz selenium.


## Alcance del proyecto:
### Entregables:
- Sistema de acompañamiento virtual
- Documentación
- Código fuente
### Fuera del alcance:
- No realiza tareas que no estén previamente definidas
- Solo funciona en la plataforma miubp3
# Recursos:
- _A definir_
### Partes interesadas y aprobadores:
- Sponsor del proyecto: Universidad Blas Pascal
- Aprobadores: Oscar Gencarelli


