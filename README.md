# KiCad Libraries
---

Este repositorio contiene una colección de librerías personalizadas para **KiCad** desarrolladas por @MrChunckuee. Incluye símbolos, huellas (footprints) y modelos 3D de componentes electrónicos que no suelen estar disponibles en las librerías oficiales de KiCad o que han sido optimizados para su fabricación.

## Contenido del Repositorio
El repositorio está organizado de la siguiente manera:
* **`Symbols/`** (`.kicad_sym`): Librerías de símbolos para el editor de esquemáticos.
* **`Footprints/`** (`.pretty`): Directorios que contienen las huellas de los componentes para el diseño de la PCB.
* **`3D_Models/`** (`.3dshapes`): Modelos en formatos STEP/WRL para la visualización en 3D de la placa.


## Compatibilidad

Las librerías han sido creadas y probadas en **KiCad versión [9.0]**. 
*Nota: Si utilizas una versión muy antigua de KiCad, es posible que los archivos no sean compatibles.*

---
## Cómo instalar y usar estas librerías

### 1. Clonar o descargar el repositorio
Descarga el repositorio como archivo ZIP o clónalo directamente en tu carpeta de componentes usando Git:
```bash
git clone https://github.com/MrChunckuee-Electronics/KiCad_Libraries.git
```

### 2. Agregar los Símbolos (Schematic Symbols)
* Abre KiCad y ve a Preferences (Preferencias) > Manage Symbol Libraries (Gestionar librerías de símbolos).
* Selecciona la pestaña Global Libraries (para usarlas en todos tus proyectos) o Project Specific (solo para el proyecto actual).
* Haz clic en el icono de la carpeta (Add empty row / Browse) y busca el archivo .kicad_sym (o .lib si es antiguo) dentro de la carpeta descargada.
* Dale un alias descriptivo (por ejemplo, MrChunckuee_Symbols).

### 3. Agregar las Huellas (Footprints)
* En KiCad, ve a Preferences > Manage Footprint Libraries (Gestionar librerías de huellas).
* Ve a la pestaña correspondiente (Global o Project Specific).
* Haz clic en el icono de la carpeta y selecciona las carpetas con terminación .pretty.
* Asígnale un alias (por ejemplo, MrChunckuee_Footprints).

### 4. Vincular Modelos 3D (Opcional)
* Para que los modelos 3D se muestren correctamente, asegúrate de configurar la ruta relativa en las propiedades del footprint de KiCad o añade la variable de entorno correspondiente apuntando a la carpeta 3D_Models.

## Web
Puedes consultar la lista completa de componentes en: https://mrchunckuee.blogspot.com/p/kicad.html
