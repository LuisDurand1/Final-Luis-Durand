# Examen Final - Proyecto Html y Css Dockerizado

Instrucciones para construir y ejecutar la imagen Docker que sirve los archivos estáticos (`index.html`, `styles.css`).

1) Abrir Terminal en la carpeta del proyecto (ejemplo):

```powershell
cd "C:\Users\Lucho\Desktop\Final-Luis-Durand"
```

2) Construir la imagen (etiqueta `final-exam`):

```powershell
docker build -t final-exam .
```

3) Ejecutar el contenedor (mapea puerto 8080 del host al 80 del contenedor):

```powershell
docker run --rm -p 8080:80 final-exam
```

4) Abrir el navegador en:

http://localhost:8080
