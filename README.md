# 🏗️ secuenciasdynamo: Pack de Modelado I

Colección de secuencias profesionales de **Dynamo para Revit** diseñadas para optimizar la productividad en tareas de modelado arquitectónico. Este pack automatiza procesos tediosos como el trazado de muros, la creación de acabados y la gestión de datos desde Excel.

---

## 🛠️ Secuencias Incluidas

### [cite_start]1. Crear muros desde un CAD [cite: 2]
[cite_start]Esta secuencia permite generar muros de Revit de forma automática basándose en las capas de un archivo CAD vinculado[cite: 2, 3].
* [cite_start]**Input:** Selección del elemento CAD mediante `Select Model Element`[cite: 4].
* [cite_start]**Lógica:** Filtra por capas (`CAD.CurvesFromCADLayers`) y genera los muros utilizando curvas y niveles específicos[cite: 3, 16].
* [cite_start]**Resultado:** Muros paramétricos (ej. Hormigón 30 cm) creados instantáneamente entre el Nivel 1 y el Nivel 2[cite: 26, 13, 21].

### [cite_start]2. Habitaciones: Crear y Etiquetar desde Excel [cite: 27]
[cite_start]Automatiza la creación de espacios en el modelo BIM utilizando bases de datos externas[cite: 27].
* [cite_start]**Etiquetar habitaciones (desde Excel):** Lee los nombres y números desde una planilla para evitar errores de transcripción manual[cite: 28].

### [cite_start]3. Crear pisos a partir de habitaciones [cite: 29]
[cite_start]Genera la geometría de suelos detectando automáticamente los límites de las habitaciones colocadas en el proyecto[cite: 30].

### [cite_start]4. Crear zócalos [cite: 31]
[cite_start]Automatización del modelado de terminaciones interiores mediante tres pasos clave[cite: 31]:
1. [cite_start]**Seleccionar todas las habitaciones:** Identifica los perímetros de trabajo[cite: 34].
2. [cite_start]**Definir Tipo de Zócalo:** Selección de la familia de acabado[cite: 32].
3. [cite_start]**Definir Altura de Zócalo:** Ajuste paramétrico de la dimensión vertical[cite: 33].

---

## 📦 Requisitos
Para que estas secuencias funcionen correctamente, asegúrate de tener instalados los siguientes nodos/paquetes:
* [cite_start]**Paquete Modelical:** Utilizado para la gestión avanzada de datos y geometría[cite: 35].
* **Revit:** Versión compatible con Dynamo 2.x o superior.

---

## 🚀 Cómo empezar
1. Descarga los archivos `.dyn` de este repositorio.
2. Abre tu proyecto en Revit.
3. Ejecuta Dynamo y carga la secuencia deseada.
4. Ajusta los nodos de selección (Inputs) y dale a **Run**.

---

## 🛒 Adquiere el Pack Completo
¿Buscas soporte técnico y guías de uso detalladas? 
👉 **[Visita mi tienda en Gumroad para descargar el pack profesional]**
