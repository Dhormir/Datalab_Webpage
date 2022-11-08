# Documentación de bibliografía de sitio de Datalab

Las publicaciones de Datalab y los academicos se muestran en el siguiente enlace: *Not yet* . Se utiliza la herramienta BibBase (<https://bibbase.org/>) para embeder en el sitio las publicaciones presentes en el archivo pubs.bib, que se encuentra en la raíz de la rama master del repositorio del sitio.

## Requisitos

Es necesario tener instalada la herramienta `bib-tool` de forma local.

Para instalar en linux pude utilizar el siguente comando:

```
sudo apt-get install bibtool
```

## Uso

Para actualizar el archivo `pubs.bib` con nuevas publicaciones es necesario seguir los siguientes pasos:

- Agregar, eliminar o actualizar los archivos individuales que se encuentran en la carpeta `bibs`.
- Dentro de la carpeta ejecutar `make pubs` para actualizar `pubs.bib`.
- Agregar los cambios, commitear y pushear hacia Github.
