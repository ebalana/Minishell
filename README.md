# Minishell
42 minishell Project - Ernest Balañá and Miquel Avellaneda

## Descripción
`minishell` es una implementación de una shell mínima que reproduce el comportamiento básico de bash. El proyecto tiene como objetivo profundizar en el manejo de procesos, señales, parsing y estructuras del sistema operativo Unix.
Este proyecto fue desarrollado como parte del currículo de la escuela 42.

## Características
- Lectura de comandos desde la entrada estándar
- Ejecución de comandos con argumentos
- Comandos encadenados con pipes (`|`)
- Redirecciones (`<`, `>`, `>>`, `<<`)
- Variables de entorno (`$VAR`)
- Comandos built-in:
  - `cd`
  - `echo`
  - `env`
  - `exit`
  - `export`
  - `pwd`
  - `unset`
- Manejo de errores y señales (`Ctrl+C`, `Ctrl+D`, `Ctrl+\`)

## 🛠️ Instalación
```bash
git clone https://github.com/tuusuario/minishell.git
cd minishell
make
