## personal resume website

### instalation of tools
* El archivo "resume.json" debe estar en la carpeta "resume" y "papirus"
* Se debe tener instalado resume-cli desde https://github.com/jsonresume/resume-cli

* Entrar a la carpeta "resume" y escribir en la terminal:

    resume export index.html -t .

    NOTA: si hay errores se tiene que revisar el formato del archivo json o usar un validador online como: https://jsonformatter.org/

* salir de la carpeta "resume" y ejecutar el escript "patch" y "patchPdf"

  ./patch
  ./patchPdf

* Para generar el pdf entrar a la carpeta "papirus" y abrir en el navegador el archivo "index.html"
  usar las opciones de impresion para generar el pdf y ponerlo en la carpeta "docs" con nombre "cvGio.pdf"

* Actualizar el repositorio
```
  git add .
  git commit -m "algun mensaje "
  git push origin master
```
* Abrir en el navegador la direccion:
  https://kristabhell12.github.io/

