# Practica-Linux-Git / Comandos básicos

1. Navegación de directorios

cd /etc           # Ir al directorio /etc
cd ~              # Volver al directorio personal

2. Listar archivos (incluidos ocultos)

ls -la            # Lista todos los archivos, incluso los ocultos

3. Crear directorios

mkdir -p practica_linux/notas   # Crea la carpeta practica_linux y dentro de ella otra llamada notas

4. Crear archivos vacíos

touch practica_linux/info.txt   # Crea un archivo vacío llamado info.txt dentro de practica_linux

5. Editar archivos

echo "Hola Linux" > practica_linux/info.txt   # Escribe "Hola Linux" en info.txt (sobrescribe si ya existe)

6. Ver el contenido de un archivo

cat practica_linux/info.txt    # Muestra el contenido del archivo

7. Eliminar archivos y carpetas

rm practica_linux/info.txt     # Borra el archivo info.txt
rmdir practica_linux/notas     # Elimina la carpeta notas (debe estar vacía)

8. Copiar archivos

cp /etc/hosts practica_linux/  # Copia el archivo hosts a la carpeta practica_linux

9. Mover archivos

mv practica_linux/hosts ~      # Mueve el archivo hosts a tu directorio personal

10. Buscar archivos

find /etc -type f -name "*.conf"   # Busca todos los archivos .conf dentro de /etc

11. Buscar texto dentro de archivos

grep "nameserver" /etc/resolv.conf   # Busca la palabra "nameserver" en el archivo indicado

12. Ver usuarios del sistema

cat /etc/passwd   # Muestra todos los usuarios registrados

13. Ver procesos activos

ps                # Muestra los procesos activos del usuario actual

14. Cambiar permisos de un archivo

chmod +x practica_linux/info.txt   # Hace que el archivo sea ejecutable

15. Ver el historial de comandos

history           # Muestra el historial de comandos
