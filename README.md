# Blender2Ogre-Build
## Repositorio
El repositorio contiene una copia de Blender en la versión 2.70 con el add-on de blender2Ogre (v0.6.0) instalado.
## Instalación
Para arrancar Blender, entrar en la carpeta *blender-2.70-windows64* y ejecutar el .exe.
## Uso
Para que genere automáticamente el .mesh, copiar la carpeta OgreCommanLineTools al directorio raiz (C:).
En caso de que no genere automáticamente el .mesh, ejecutar desde consola el ejecutable OgreXMLConverter.exe con 
el xml del mesh como argumento. Hacer lo mismo con el .xml del esqueleto:
```shell
C:\Path\OgreCommandLineTools>OgreXMLConverter.exe archivo.mesh

