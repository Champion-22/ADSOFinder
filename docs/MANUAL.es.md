# Advanced DSO Finder - Manual de Usuario

¡Bienvenido al manual de usuario oficial de Advanced DSO Finder! Este documento te guiará a través de todas las funciones de la aplicación, desde la configuración de tu ubicación hasta el análisis de objetos astronómicos.

**Idiomas:** [Deutsch](MANUAL.de.md) | [English](MANUAL.en.md) | [**Español**](MANUAL.es.md) | [Français](MANUAL.fr.md) | [日本語](MANUAL.ja.md)

---

## Índice

1.  [Primeros Pasos: La Interfaz de Usuario](#1-primeros-pasos-la-interfaz-de-usuario)
2.  [Configurar Ubicación y Hora](#2-configurar-ubicación-y-hora)
    *   [Entrada Manual](#entrada-manual)
    *   [Búsqueda de Ubicación y Autodetección](#búsqueda-de-ubicación--autodetección)
    *   [Ajustes de Hora](#ajustes-de-hora)
3.  [Filtrar Objetos](#3-filtrar-objetos)
    *   [Escala de Bortle y Magnitud Límite](#escala-de-bortle--magnitud-límite)
    *   [Altitud y Tamaño del Objeto](#altitud-y-tamaño-del-objeto)
    *   [Iluminación Lunar](#iluminación-lunar)
    *   [Tipos de Objetos](#tipos-de-objetos)
    *   [Dirección Cardinal](#dirección-cardinal)
4.  [Entender y Usar los Resultados](#4-entender-y-usar-los-resultados)
    *   [Lista de Resultados](#lista-de-resultados)
    *   [Detalles del Objeto](#detalles-del-objeto)
    *   [Análisis Gráfico (Plots)](#análisis-gráfico-plots)
5.  [Las Pestañas de Herramientas](#5-las-pestañas-de-herramientas)
    *   [Entrada Manual de Objetivo](#entrada-manual-de-objetivo)
    *   [Calculadora de Corrimiento al Rojo](#calculadora-de-corrimiento-al-rojo)
    *   [Calculadora de Horas de Sol](#calculadora-de-horas-de-sol)
6.  [Resolución de Problemas (FAQ)](#6-resolución-de-problemas-faq)

---

### 1. Primeros Pasos: La Interfaz de Usuario

La interfaz se divide en dos áreas principales:
*   **Barra Lateral Izquierda:** Aquí encontrarás todos los campos de entrada y filtros para definir tu búsqueda.
*   **Área Principal Derecha:** Esta área muestra los resultados de la búsqueda y herramientas adicionales en pestañas.

![Interfaz de la App](screenshots/Spanisch_1.png)

---

### 2. Configurar Ubicación y Hora

La precisión de todos los cálculos depende de una ubicación y fecha exactas.

#### Entrada Manual
Introduce tu **Latitud** y **Longitud** directamente en los campos correspondientes.
*   Las latitudes norte y longitudes este son positivas (p. ej., `47.05`).
*   Las latitudes sur y longitudes oeste son negativas (p. ej., `-33.92`).
La **Elevación** sobre el nivel del mar en metros mejora la precisión de los cálculos, especialmente cerca del horizonte.

#### Búsqueda de Ubicación & Autodetección
*   **Buscar:** Introduce el nombre de un lugar o ciudad en el campo de búsqueda y haz clic en "Buscar". La aplicación rellenará las coordenadas automáticamente.
*   **Auto-detectar:** Haz clic en "Auto-detectar" para determinar tu ubicación aproximada a través de tu dirección IP. Es rápido y cómodo, pero puede ser menos preciso que una búsqueda manual.

#### Ajustes de Hora
*   **Ahora (esta noche):** Utiliza la noche actual (desde el atardecer hasta el amanecer) para el cálculo.
*   **Noche específica:** Haz clic aquí para revelar un campo de entrada de fecha. Al hacer clic en el campo, se abre un calendario para seleccionar fácilmente cualquier fecha.

---

### 3. Filtrar Objetos

Usa los filtros para acotar la búsqueda a los objetos celestes que te interesan.

#### Escala de Bortle & Magnitud Límite
La **Escala de Bortle** es una medida de la contaminación lumínica en tu ubicación (1 = cielo oscuro excelente, 9 = centro de ciudad). La aplicación calcula automáticamente una **magnitud límite** realista para la visibilidad con un telescopio. Solo se mostrarán los objetos más brillantes que este valor.

#### Altitud y Tamaño del Objeto
*   **Alt Mín:** Define la altitud mínima que un objeto debe tener sobre el horizonte para aparecer en los resultados. Se recomienda un valor de `20°` o `30°` para evitar la neblina y los obstáculos cercanos al horizonte.
*   **Alt Máx:** La altitud máxima que un objeto puede alcanzar. Normalmente se deja en `90°` (cenit).
*   **Tamaño Mín/Máx:** Filtra los objetos por su tamaño aparente en el cielo en minutos de arco. Útil para encontrar solo objetos grandes y extensos o nebulosas planetarias pequeñas.

#### Iluminación Lunar
*   **Ilum. lunar máx. (%):** Un filtro crucial. Si la iluminación de la luna en la noche seleccionada supera este valor, no se mostrarán resultados, ya que la luna opacaría los objetos débiles. Establece el valor en `10%` para observar galaxias débiles o en `100%` si solo buscas objetos brillantes.

#### Tipos de Objetos
Selecciona las categorías de objetos celestes que te interesan (p. ej., Galaxias, Nebulosas, Cúmulos). Usa los botones "Seleccionar todo" y "No seleccionar ninguno" para hacer ajustes rápidos.

#### Dirección Cardinal
Restringe la búsqueda a objetos que alcanzan su punto más alto en una dirección cardinal específica (p. ej., "Sur"). Ideal si tu lugar de observación está obstruido en una dirección.

---

### 4. Entender y Usar los Resultados

Después de hacer clic en "Buscar", los resultados aparecerán en el área principal derecha.

#### Lista de Resultados
Por defecto, los objetos se ordenan por una combinación de duración de visibilidad y altitud máxima. Puedes cambiar la ordenación a "Brillo".
Cada entrada muestra el nombre, tipo y magnitud del objeto. Haz clic en una entrada para expandirla.

#### Detalles del Objeto
En la vista expandida, verás información detallada:
*   **Alt. máx.:** La posición más alta que el objeto alcanza durante la noche.
*   **Mejor hora (local):** La hora a la que el objeto alcanza esta altitud máxima. Este es el momento óptimo para la observación.
*   **Duración visible:** El número de horas que el objeto está visible sobre el horizonte.
*   **Constelación, Tamaño, AR/Dec:** Datos astronómicos adicionales.

#### Análisis Gráfico (Plots)
*   **Perfil de altitud:** Muestra un gráfico de la altitud del objeto a lo largo de la noche. Ideal para visualizar la mejor ventana de observación.
*   **Trayectoria celeste:** Muestra la trayectoria del objeto a través del cielo desde su salida hasta su puesta.

---

### 5. Las Pestañas de Herramientas

#### Entrada Manual de Objetivo
Busca un objeto específico (p. ej., "NGC 224") o introduce coordenadas de AR/Dec directamente para calcular la visibilidad de cualquier objetivo. También puedes guardar y cargar objetivos de uso frecuente aquí.

#### Calculadora de Corrimiento al Rojo
Una herramienta para los interesados en la cosmología. Introduce un corrimiento al rojo (z) para calcular distancias cosmológicas y el tiempo de retroceso. Los contextos descriptivos indican de qué era del universo proviene la luz.

#### Calculadora de Horas de Sol
Calcula las horas exactas de amanecer, atardecer, mediodía solar y la duración del día para la ubicación y fecha seleccionadas.

---

### 6. Resolución de Problemas (FAQ)

*   **P: ¿Por qué no obtengo ningún resultado?**
    *   **R:** Revisa tus filtros. Las causas más comunes son:
        1.  La Luna está demasiado brillante (`Ilum. lunar máx.` está ajustado muy bajo).
        2.  El filtro `Alt Mín` está ajustado muy alto.
        3.  No hay tipos de objetos seleccionados.
        4.  La noche seleccionada es durante el verano en una región cercana a los polos donde no oscurece.

*   **P: La autodetección de mi ubicación es imprecisa.**
    *   **R:** La geolocalización basada en IP puede ser inexacta. Para obtener resultados precisos, utiliza la búsqueda manual de tu localidad o introduce tus coordenadas directamente.

---
¿Has encontrado un error o tienes una sugerencia de mejora? Por favor, crea un [Issue en GitHub](https://github.com/Champion-22/ADSOFinder/issues).
