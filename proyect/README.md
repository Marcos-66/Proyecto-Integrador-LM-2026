# Proyecto Integrador: Especificaciones y Estructura

Este repositorio contiene la entrega inicial del proyecto para la asignatura **Lenguajes de Marcas**. El objetivo es construir un sitio web evolutivo que integrará tecnologías web a lo largo del curso, partiendo de una base de marcado estructurado en HTML5 y almacenamiento de datos semánticos en XML.

---

## 1. Información del Estudiante y Proyecto
* **Autor:** Marcos Carmona Cáceres
* **Usuario de GitHub:** Marcos-66
* **Temática de la Web:** Rastreo de ubicación GPS

### Justificación del Tema
Me parece una propuesta muy interesante, el uso del gps como forma de rastreo es muy utilizado gracias 
a su gran veracidad y facilidad. Por esto he elegido este proyecto, ya que realizar este programa es una forma de 
aumentar mis conocimientos, creando algo útil para la sociedad.

---

## 2. Control de Asistencia (Reto 1)
* **Palabra del día:**  Contexto 

---

## 3. Arquitectura de Archivos y Carpetas
El proyecto se organiza bajo la siguiente estructura de directorios obligatoria:
* `proyecto/`: Carpeta contenedor principal del módulo.
  * `index.html`: Documento web principal y punto de entrada del sitio.
  * `datos.xml`: Almacenamiento de la base de datos local con etiquetas personalizadas.
  * `img/`: Directorio destinado a optimizar y almacenar los recursos gráficos locales.
  * `README.md`: Este archivo técnico informativo de la entrega.

---

## 4. Desglose del Archivo: index.html (Reto 2)
La página principal se ha desarrollado bajo el estándar **HTML5** y cumple con los siguientes elementos informativos:
* **Declaración de Tipo e Idioma:** Uso de `<!DOCTYPE html>` y configuración del atributo de idioma en español (`lang="es"`).
* **Metadatos Técnicos:** Configuración de juego de caracteres en `UTF-8` para evitar fallos de codificación y `viewport` para la adaptabilidad en dispositivos móviles.
* **Estructura Semántica:** Títulos jerárquicos (`h1` y `h2`) acompañados de párrafos introductorios con marcas de énfasis (`strong` y `em`).
* **Elementos Multimedia y Enlaces:** Inserción de una imagen local optimizada (con textos alternativos `alt`) y dos hipervínculos: uno externo de referencia documental y uno interno para navegar al origen de datos XML.

---

## 5. Desglose del Archivo: datos.xml (Reto 3)
El archivo de datos se ha diseñado siguiendo estrictamente las reglas de un documento **bien formado** en XML:
* **Prólogo XML:** Declaración de versión y codificación en la primera línea del documento.
* **Elemento Raíz Personalizado:** Nodo principal que engloba toda la información, identificado mediante el atributo obligatorio `propietario` vinculado al usuario de GitHub.
* **Estructura de Nodos:** Modelado de tres elementos equivalentes provistos de identificadores únicos (`id`), compuestos por nodos hijos que mezclan datos textuales, elementos vacíos auto-cerrados de marcado (flags) y datos numéricos formateados con precisión decimal y atributos de unidad de medida explícitos.

---

## 6. Trabajo Realizado en esta Entrega (Reto 4)
En esta primera fase del proyecto integrador, se ha establecido la arquitectura inicial del repositorio en GitHub. Se ha completado el diseño visual e informativo básico en la página de inicio en HTML y se ha mapeado con éxito su correspondiente réplica de almacenamiento de información en formato XML, verificando la ausencia de errores de sintaxis y anidamiento en el panel de problemas del entorno de desarrollo.


## document.compatMode
'CSS1Compat'
Sginifica que la página incluye <!DOCTYPE html> en la primera linea.

## 3 cosas que me faltan:
Metadatos
Jerarquía de títulos
Bloques

## Mapa del sitio
|Fichero              |Title                                            |Que contiene                                                    |
|---------------------|-------------------------------------------------|----------------------------------------------------------------|
|index.html           |Safezone                                         |Portada: bienvenida, características, funcionamientos, ventajas.|
|datos.html           |Datos de la página                               |Contenido de datos.xml                                          |
|rastreo.html         |Rastreo a tiempo real                            |Info de la caracteristica de rastreo.                           |
|notificacion.html    |Notificaciones de seguridad y alertas            |Info de la caracteristica de notificaciones y alertas.          |
|mapa.html            |Mapa interactivo                                 |Info de la caracteristica del mapa interactivo.                 |
|sos.html             |Boton SOS                                        |Info de la caracteristica del boton SOS.                        |
|interfaz.html        |Personalización de la interfaz                   |Info de la caracteristica de personalización de la interfaz.    |
|chats.html           |Posibilidad de crear chats y realizar llamadas   |Info de la caracteristica de la creación de chats y llamadas.   |

## UD3: Estucctura HTML
Errores: 
En el fichero de datos.html me he equivocado en algunos campso y no los he puesto correctamente.
Ademas en el index.html no he anidado bien algunos campos como <p> o <br>

Que he realizado: 
En este trabajo he actualizado mi página web añadiendole más contenido gracias al temario que se nos a estado mostrando en clase un ejemplo de esto seria los <blockquote> o los <div> entre otros.