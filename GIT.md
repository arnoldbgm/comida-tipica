# Comandos de Git

Para clonar un repositorio usamos
```
git clone <url>
```

Para subir un archivo o archivos a nuestro repositorio remoto, seguimos el metodo ACP

Para verificar que archivos son nuevos o tienen cambios, ejecutamos un 

```
git status
```

---
## 🚀 Paso 01 Flujo ACP (add)
Selecciono que voy a subir
```
git add  <nombre_archivo>

git add .
```

## 🦇 Paso 02 Flujo ACP (commit)
Escribimos el comentario con que se subira este archivo a git
```
git commit -m "Comentario"
```

## 💚 Paso 03 Flujo ACP (push)
Enviamos los cambios de nuestro repositorio local al repositorio remoto
```
git push origin <rama>
```
Gracias por visitar nuestra documentacion