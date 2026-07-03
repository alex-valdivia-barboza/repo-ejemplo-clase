# 📖 Chuleta de conceptos de GitHub

## Los básicos

- **Repositorio (repo):** carpeta de proyecto en la nube, con historial completo de cambios.
- **Commit:** una "foto" de tus cambios en un momento dado, con un mensaje que explica qué hiciste.
- **Rama (branch):** una línea de trabajo paralela. La principal se llama `main`.
- **README.md:** la portada del proyecto. Se escribe en Markdown y GitHub la muestra automáticamente.
- **Markdown:** lenguaje simple para dar formato: `#` para títulos, `**negrita**`, `- listas`.

## El menú "+" de GitHub

- **New repository:** crear un repo desde cero.
- **Import repository:** traer un repo desde otra plataforma (GitLab, Bitbucket) o desde una URL Git.
- **New issue:** abrir un ticket para reportar un bug o proponer una mejora en un repo.
- **New codespace:** entorno de desarrollo (VS Code) en la nube, dentro del navegador.
- **New gist:** compartir un fragmento de código suelto, sin crear un repo completo.
- **New organization:** cuenta compartida para equipos/empresas que agrupa repos y miembros.
- **New project:** tablero kanban (estilo Trello) integrado con los issues de tus repos.

## Conexión con Google Colab

| Acción | Cómo |
|--------|------|
| Guardar notebook de Colab en GitHub | Archivo → Guardar una copia en GitHub |
| Abrir notebook de GitHub en Colab | Archivo → Abrir notebook → pestaña GitHub |
| Truco de URL | Cambiar `github.com` por `colab.research.google.com/github` |
| Clonar repo dentro de Colab | `!git clone https://github.com/USUARIO/REPO.git` |

## Comandos Git esenciales (para la próxima sesión)

```bash
git clone <url>      # descargar un repo
git add .            # preparar cambios
git commit -m "msg"  # guardar la "foto" con mensaje
git push             # subir los commits a GitHub
git pull             # traer los cambios más recientes
```
