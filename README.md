# Auto Logistics Upgrade - Hearts of Iron IV Mod

Este mod introduce un sistema avanzado de **automatización logística** para Hearts of Iron IV. Permite al jugador reservar un cupo específico de Fábricas Civiles para que el sistema gestione de forma autónoma la construcción y mejora de infraestructuras críticas (vías de tren, nodos de suministro e infraestructuras en estados prioritarios) sin requerir microgestión constante.

## Características Principales
* **Cola de Construcción Virtual**: Asigna de 0 a 15 fábricas civiles que desaparecerán de la cola manual y producirán progreso industrial en segundo plano.
* **Priorización Inteligente (Fase 1)**: El sistema identifica cuellos de botella en nodos de suministro y construye/mejora vías de tren de manera prioritaria.
* **Mejoras de Infraestructura (Fase 2)**: Cuando las vías de tren están optimizadas, invierte en infraestructura en estados estratégicos (aquellos con presas, recursos estratégicos como petróleo y goma, con espacios de construcción libres, o donde hay combates activos).
* **Integración Limpia en la Interfaz**: Accede a un nuevo panel integrado en la vista de construcción para ajustar tus fábricas asignadas con un clic.

## Instalación (Rápida)

Para instalar el mod, debes descargar ambos archivos de la última release y colocarlos en la carpeta correcta:

1. Ve a la pestaña **Releases** de este repositorio en GitHub.
2. Descarga los archivos **`AutoSupply.zip`** y **`AutoSupply.mod`**.
3. Coloca *ambos* archivos (sin descomprimir el `.zip`) directamente en tu directorio de mods de Hearts of Iron IV:
   - **Windows:** `C:\Usuarios\<TuUsuario>\Documentos\Paradox Interactive\Hearts of Iron IV\mod\`
   - **Linux:** `~/.local/share/Paradox Interactive/Hearts of Iron IV/mod/`
   - **Mac:** `~/Documents/Paradox Interactive/Hearts of Iron IV/mod/`
4. Abre el Launcher de HOI4, ve a "Playsets" (Colecciones), añade el mod "Auto Logistics Upgrade" y actívalo.

*(Nota: Si no existe el directorio `mod`, puedes crearlo manualmente).*

## Uso en el Juego
1. Abre el menú de **Construcción** (`Atajo: T` por defecto).
2. En la parte inferior, verás el nuevo panel de **Auto Logística**.
3. Usa los botones `+` y `-` para asignar la cantidad de fábricas civiles que deseas destinar al proyecto (máximo 15).
4. El mod te informará en todo momento sobre qué infraestructura se está mejorando actualmente.

## Compatibilidad
* Desarrollado para Hearts of Iron IV v1.19.*
* Debería ser compatible con la mayoría de mods que no alteren por completo la interfaz `countryconstructionsview.gui` o el sistema base de fábricas.

---
*Desarrollado según las especificaciones técnicas de diseño.*
