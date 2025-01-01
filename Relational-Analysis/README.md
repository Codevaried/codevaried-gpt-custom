# **Análisis Relacional**

### **Nombre**

Análisis Relacional

### **Descripción**

Agente especializado en análisis psicológico de conversaciones, que evalúa relaciones y comunicación. Identifica habilidades, calcula compatibilidad e incompatibilidad, y ofrece informes profesionales con fortalezas, desafíos y recomendaciones para mejorar la interacción.

---

### **Instrucciones**

El agente sigue las directrices descritas en el archivo [`promt.md`](core/promt.md).

---

### **Iniciadores de Conversación**

Usa estas frases para interactuar con el agente y aprovechar al máximo sus capacidades:

- **"Analiza esta conversación y evalúa las habilidades de ambas personas."**
- **"¿Qué tan compatibles son estas personas según su conversación?"**
- **"Dame un informe completo de esta interacción con fortalezas y mejoras."**
- **"Calcula el índice de incompatibilidad de este diálogo."**
- **"Resume las diferencias y similitudes entre estas dos personas."**

---

### **Conocimiento**

El agente utiliza recursos descritos en la carpeta [`files`](core/files), incluyendo plantillas como:

- `Template_AnalysisRelationshipCommunication.md`: Estructura detallada para generar informes claros y profesionales.

---

### **Funciones**

El agente cuenta con las siguientes capacidades habilitadas y deshabilitadas:

- [ ] **Búsqueda en Internet**
- [ ] **Lienzo**
- [x] **Generación de imágenes de DALL·E**
- [ ] **Intérprete de código y análisis de datos**

---

### **Acciones**

El agente realiza cálculos matemáticos precisos utilizando la acción definida en [`actions`](core/actions):

- **api.mathjs.org**: Servicio externo para resolver expresiones matemáticas y cálculos relacionados.

---

### **Configuración Adicional**

- [ ] **Utilizar los datos de la conversación en tu GPT para mejorar nuestros modelos**  
       _(Actualmente, esta opción está deshabilitada para garantizar privacidad y seguridad.)_

---

### **Notas**

Este agente es una herramienta poderosa para análisis relacional. Si tienes ideas para expandir su funcionalidad o mejorar su configuración, ¡no dudes en contribuir!
