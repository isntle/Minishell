# Proyecto Minishell

Este proyecto consiste en un minishell desarrollado completamente en lenguaje C, inspirado en Bash. Fue implementado como parte de la materia de Sistemas Operativos en la ESCOM-IPN, y presentado en ExpoESCOM 2025.

## ¿Qué hace?

Permite ejecutar comandos en una terminal personalizada, con funcionalidades avanzadas como:

- Historial de comandos
- Navegación con flechas izquierda/derecha y edición en tiempo real
- Redirección de entrada y salida (`<`, `>`, `>>`, `<<`)
- Manejo de tuberías (`|`)
- Comandos internos (`cd`, `exit`)
- Soporte para comillas dobles/simples y argumentos con espacios
- Captura de señales como `SIGINT` (Ctrl+C)
- Entrada carácter por carácter con `termios.h`

## Compilación

```bash
gcc minishell.c -o minishell
````

## Ejecución

```bash
./minishell
```

Una vez ejecutado, podrás ingresar comandos como si estuvieras en Bash.

## Tecnologías y conceptos aplicados

* Programación en C
* Manipulación de terminal (`termios.h`)
* Manejo de procesos (`fork`, `execvp`, `waitpid`)
* Redirección estándar (`dup2`)
* Tuberías (`pipe`)
* Señales (`signal`)
* Análisis de línea y segmentación por tokens

## Autor
**Mérida de León Luis Ernesto**

Estudiante de Ingeniería en Sistemas Computacionales

ESCOM – Instituto Politécnico Nacional

## Acceso al código fuente
El contenido de este repositorio está protegido para evitar plagio.

Si deseas visualizar el código fuente completo, por favor solicítame acceso directamente para poder invitarte al repositorio privado.

Link del repositorio privado: https://github.com/isntle/Codigo-Minishell

