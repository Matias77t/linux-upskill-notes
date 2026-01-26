# Día 2 – Usuarios y permisos
**Fecha:** 22/01/2026

## Comandos ejecutados

```bash
# Crear un usuario nuevo
sudo adduser juan

# Cambiar contraseña del usuario
sudo passwd juan

# Crear archivo de prueba
touch archivo.txt

# Cambiar permisos del archivo
chmod 755 archivo.txt
chmod u+x archivo.txt

# Cambiar propietario del archivo
sudo chown juan:juan archivo.txt

# Ver permisos y propietarios
ls -l



✅ Explicación de comandos:  
- `adduser` → crea un usuario  
- `passwd` → cambia la contraseña  
- `chmod` → cambia permisos  
- `chown` → cambia dueño/grupo  
- `ls -l` → ve permisos y propietarios  
- `echo` "texto" >> archivo.txt → agregar texto a un archivo
- `su`  usuario → cambiar de usuario
- `cat` archivo.txt → ver contenido
---


## Explicación en mis palabras

- `sudo adduser juan` → crea un usuario llamado juan  
- `sudo passwd juan` → asigna contraseña al usuario  
- `chmod 755 archivo.txt` → permisos: dueño puede leer/escribir/ejecutar, otros pueden leer/ejecutar  
- `chmod u+x archivo.txt` → da permiso de ejecución al dueño  
- `sudo chown juan:juan archivo.txt` → cambia dueño y grupo del archivo  
- `ls -l` → muestra permisos y propietarios de los archivos

## Aprendizajes clave

- Entendí cómo crear usuarios y asignarles contraseñas  
- Aprendí a cambiar permisos y dar ejecución a archivos  
- Comprendí cómo cambiar dueño y grupo de archivos  
- Aprendí la importancia de documentar cada paso en el `.md`
