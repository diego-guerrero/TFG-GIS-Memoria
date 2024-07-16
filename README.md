# Trabajo Fin de Grado - Grado en Ingeniería del *Software*

**Título del trabajo**: VSCode4Teaching: mantenimiento y evolución de la herramienta para la enseñanza de la programación en línea.  
**Autor**: Diego Guerrero Carrasco ([correo electrónico](mailto:diegogcarrasco@icloud.com), [perfil en GitHub](https://github.com/diego-guerrero), [perfil en LinkedIn](https://www.linkedin.com/in/diego-guerrero-carrasco/)).  
**Titulación**: Grado en Ingeniería del *Software* (dentro del Doble grado en Ingeniería Informática e Ingeniería del *Software*), Escuela Técnica Superior de Ingeniería Informática, Universidad Rey Juan Carlos (Madrid, España).  
**Defendido** el martes 16 de julio de 2024 en el Campus de Móstoles de la Universidad Rey Juan Carlos.

El presente repositorio contiene los ficheros fuente empleados para la generación de la memoria del Trabajo Fin de Grado correspondiente al Grado en Ingeniería del *Software*.


## Resumen
[*VSCode4Teaching*](https://github.com/codeurjc-students/2019-VSCode4Teaching) es una extensión para el entorno de desarrollo integrado Visual Studio Code que tiene como objetivo facilitar y potenciar la enseñanza de la disciplina de la programación, contribuyendo así a la mejora de la educación en competencias digitales y en el ámbito de la informática, área que vive un incipiente crecimiento causado por su veloz y revolucionaria implantación y extensión a nivel universal.

En *VSCode4Teaching*, los docentes pueden crear, mantener y supervisar cursos compuestos por ejercicios que los estudiantes matriculados completarán para aprender. Para ello, los profesores proponen una plantilla inicial a cada ejercicio sobre la que los estudiantes construyen la solución que consideren válida, sincronizándola durante su realización para mantener al profesor informado en tiempo real hasta finalizarla.

El presente documento describe de forma pormenorizada todas las cuestiones relativas al tercer trabajo de evolución y adaptación realizado sobre *VSCode4Teaching*, que introduce nuevas características y refina la funcionalidad de esta herramienta para aumentar su alcance y potenciar su usabilidad y mantenibilidad.

Este proyecto tiene una fisonomía de aplicación web compuesta de tres componentes: un servidor, encargado del intercambio, persistencia e interpretación de los datos, una extensión para Visual Studio Code y una aplicación web que permite ampliar la funcionalidad de la aplicación más allá del editor de código.

*VSCode4Teaching* es un proyecto de *software* libre sujeto a la licencia Apache 2.0 a través de un [repositorio público de GitHub](https://github.com/codeurjc-students/2019-VSCode4Teaching) que contiene, además, la documentación necesaria para que otros desarrolladores puedan ejecutar y desplegar la aplicación, pudiendo adaptarla a sus intereses.


## Recursos asociados
- Código fuente del proyecto VSCode4Teaching tras finalizar este Trabajo Fin de Grado: [https://github.com/diego-guerrero/TFG-GIS-VSCode4Teaching](https://github.com/diego-guerrero/TFG-GIS-VSCode4Teaching).


## Publicación en abierto
La memoria queda publicada en abierto en el Repositorio Institucional de la Universidad Rey Juan Carlos, siendo públicamente consultable a través del siguiente enlace: [https://hdl.handle.net/10115/38212](https://hdl.handle.net/10115/38212).

Este repositorio complementa esta publicación mediante la divulgación en abierto de todos los recursos empleados para generar la memoria.


## Licencia
Este documento y todos los recursos de elaboración propia empleados para su confección se divulgan bajo licencia **CC-4.0-BY-SA** (*Atribución-CompartirIgual 4.0 Internacional* de Creative Commons), tal como se constata dentro del propio documento y como se especifica detalladamente en el fichero anexo [`LICENSE`](LICENSE).


## Organización del repositorio
El presente repositorio incluye todo el código fuente y recursos empleados para la confección de la memoria de este Trabajo Fin de Grado. Se distribuyen de la siguiente forma:
- [`2024_TFG_GIS_DiegoGuerreroCarrasco.pdf`](2024_TFG_GIS_DiegoGuerreroCarrasco.pdf). Es el documento compilado de LaTeX que contiene la memoria íntegra. Esta misma memoria ha sido la depositada en la Universidad Rey Juan Carlos para su defensa y calificación.
- [`2024_TFG_GIS_DiegoGuerreroCarrasco.tex`](2024_TFG_GIS_DiegoGuerreroCarrasco.tex). Es el fichero raíz de LaTeX que determina los datos básicos y la estructura de la memoria.
- [`secciones`](secciones/). Es la carpeta que recoge todos los contenidos textuales de la memoria de forma jerarquizada en ficheros `.tex` separados por la sección y subsecciones a las que pertenecen. Se puede seguir la jerarquía de importaciones desde el fichero raíz hacia abajo de forma arborescente.
- [`imagenes`](imagenes/). Es el directorio que incluye todas las imágenes utilizadas para la memoria. Contiene dos subdirectorios:
    - [`utilizadas`](imagenes/utilizadas/). Recoge todas las imágenes empleadas en la memoria, categorizándolas por la sección y/o subsección en que se ubican dentro de la estructura de la memoria.
    - [`originales`](imagenes/originales/). Incluye todos los recursos originales que han dado lugar a las imágenes finalmente empleadas. Entre estos recursos hay capturas de pantalla originales, montajes realizados utilizando Pixelmator Pro (`*.pxd`) y otrs recursos de interés para la generación de las figuras y tablas incluidas.