# ⚙️ PROTOCOLO OPERATIVO: GESTIÓN DE BÓVEDA (Ajota)

## 🎯 Objetivo
Este archivo define las reglas de mantenimiento, organización y procesamiento de datos para la CLI de Gemini dentro de la boveda de Obsidian.

---

## 🏗️ Estructura y Taxonomía
La IA debe respetar y aplicar la siguiente estructura de organización:

1. **Frontmatter (YAML):** Todas las notas nuevas deben incluir:
   - `type:` (médica, literaria, técnica, diario)
   - `status:` (borrador, en_progreso, finalizado)
   - `tags:` (mínimo 2 etiquetas relevantes)
   - `created:` (fecha actual)

2. **Interconexión (Links):** - Priorizar el uso de `[[Wikilinks]]` para conectar conceptos de Medicina con Literatura o Tecnología.
   - Si se menciona un órgano, buscar conexión con notas de Morfofisiología.

3. **Atomicidad:** Fomentar la creación de notas atómicas (una idea por nota) para evitar muros de texto, facilitando la lectura con astigmatismo/TDAH.

---

## 🛠️ Reglas de Mantenimiento (Strict Rules)

- **Regla de Cálculo:** Prohibido el cálculo manual. Para organizar cronogramas o mediciones, ejecutar script de Python.
- **Formateo TDAH/Disgrafía:** - Uso obligatorio de títulos (`##`, `###`).
  - Listas con viñetas para pasos secuenciales.
  - **Negritas** para conceptos terminológicos clave.
- **Gestión de Tareas:** Las tareas deben seguir el formato `- [ ]` y estar categorizadas por urgencia (Matriz de Eisenhower).
- **Cero Omisión:** Al editar o mover contenido entre notas, NO resumir ni recortar información técnica médica o literaria a menos que se pida explícitamente.

---

## 📂 Áreas de Enfoque Operativo

### 1. Academia (Medicina y UPEL)
- **Mantenimiento:** Organizar notas de Morfofisiología por sistemas (SNC, Cabeza, Cuello).
- **Acción:** Generar resúmenes de estudio tipo "Flashcard" al final de notas extensas.

### 2. Creativo (Gears of Loyalty / Ludoliteratura)
- **Mantenimiento:** Mantener un índice (MOC - Map of Content) actualizado para la novela y el proyecto de investigación.
- **Acción:** Verificar consistencia de nombres y términos técnicos en el lore.

### 3. Sistema (GeminiVault)
- **Mantenimiento:** Documentar cambios en el código de la CLI dentro de la carpeta `técnica/desarrollo`.

---

## 🛑 Restricciones de Contexto
- **Exclusión:** Ignorar cualquier referencia al PNA o INCES. Esos procesos están cerrados.
- **Privacidad:** No procesar datos sensibles de terceros mencionados en la boveda más allá de la organización lógica.
- **Tono:** Técnico, exhaustivo y orientado a la productividad.

---