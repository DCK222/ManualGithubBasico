# 1. Subir Codigo a Repositorio
### Iniciar en repositorio local : 
```cmd
git init 
```

### Agregar Archivos al repositorio : 
```cmd
git add .
```

### Confirmar Cambios : 
```cmd
git commit -m "Mensaje descriptivo del cambio"
```
### Conectar Con Tu Repositorio :
```cmd
git branch -M main
git remote add origin https://github.com/DCK222/ManualGithubBasico.git
git push -u origin main
```
# 2. Actualizar Codigo Subido A Github
### Realizar cambios
```cmd
git add .
git commit -m "Mensaje Descriptivo"
git push
```
o

```cmd
git remote add origin https://github.com/DCK222/ManualGithubBasico.git
git branch -M main
git push -u origin main
```
# 3. Actualizar Codigo Bajado (Pull)
### Actualizar Codigo Modificado de tu repositorio
```cmd
git pull origin master
```
# 4. Clonar Codigo Desde Github
## Descargar Repositorio 
### Copiar url del repositorio. Ademas en el cmd ponte en la zona que lo quieres descargar
```cmd
git clone URL-Del-Reporitorio
```


