# 🏗️ secuenciasdynamo: Pack de Modelado I

Colección de secuencias profesionales de **Dynamo para Revit** diseñadas para optimizar la productividad en tareas de modelado arquitectónico. Este pack automatiza procesos tediosos como el trazado de muros, la creación de acabados y la gestión de datos desde Excel.

---

## 🛠️ Secuencias Incluidas

### 1. Crear muros desde un CAD 
Esta secuencia permite generar muros de Revit de forma automática basándose en las capas de un archivo CAD vinculado.

* **Input:** Selección del elemento CAD mediante `Select Model Element`.
* **Lógica:** Filtra por capas (`CAD.CurvesFromCADLayers`) y genera los muros utilizando curvas y niveles específicos.
* **Resultado:** Muros paramétricos (ej. Hormigón 30 cm) creados instantáneamente entre el Nivel 1 y el Nivel 2.

### 2. Habitaciones: Crear y Etiquetar desde Excel
Automatiza la creación de espacios en el modelo BIM utilizando bases de datos externas.
***Etiquetar habitaciones (desde Excel):** Lee los nombres y números desde una planilla para evitar errores de transcripción manual.

### 3. Crear pisos a partir de habitaciones
Genera la geometría de suelos detectando automáticamente los límites de las habitaciones colocadas en el proyecto.

### 4. Crear zócalos
Automatización del modelado de terminaciones interiores mediante tres pasos clave:
1. **Seleccionar todas las habitaciones:** Identifica los perímetros de trabajo.
2. **Definir Tipo de Zócalo:** Selección de la familia de acabado.
3. **Definir Altura de Zócalo:** Ajuste paramétrico de la dimensión vertical.

---

## 📦 Requisitos
Para que estas secuencias funcionen correctamente, asegúrate de tener instalados los siguientes nodos/paquetes:
***Paquete Modelical:** Utilizado para la gestión avanzada de datos y geometría.
***Revit:** Versión compatible con Dynamo 2.x o superior.

---

## 🚀 Cómo empezar
1. Descarga los archivos `.dyn` de este repositorio.
2. Abre tu proyecto en Revit.
3. Ejecuta Dynamo y carga la secuencia deseada.
4. Ajusta los nodos de selección (Inputs) y dale a **Run**.

---

## 🛒 Adquiere el Pack Completo
¿Buscas soporte técnico y guías de uso detalladas? 
👉 **Visita mi tienda en Gumroad para descargar el pack profesional https://jomviz.gumroad.com/**
