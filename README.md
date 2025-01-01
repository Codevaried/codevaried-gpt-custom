# **Codevaried GPT Custom Actions**

### **Descripción**

Este repositorio contiene una colección de agentes GPT personalizados diseñados para casos de uso específicos. Cada agente está cuidadosamente configurado con acciones integradas, políticas de privacidad, plantillas y documentación para facilitar su implementación y personalización.

### **Estructura del Repositorio**

```tree
codevaried-gpt-custom
│
├── README.md                    # Documentación principal del repositorio
│
└── Relational-Analysis          # Agente: Análisis Relacional
    ├── README.md                # Documentación específica del agente
    ├── core/                    # Núcleo del agente
    │   ├── promt.md             # Prompt inicial del agente
    │   └── files/               # Recursos del agente
    │       └── Template_AnalysisRelationshipCommunication.md
    └── actions/                 # Acciones y configuración de API
        ├── privacy.html         # Política de privacidad del agente
        └── api.mathjs.org/      # Integración con Math.js
            └── schema.json      # Esquema OpenAPI de Math.js
```

---

### **Agentes Disponibles**

1. **[Relational Analysis](Relational-Analysis/README.md)**  
   Agente especializado en análisis psicológico de conversaciones. Evalúa habilidades comunicativas, calcula índices de compatibilidad, y genera informes detallados con recomendaciones.
   - **Acción integrada:** [api.mathjs.org](Relational-Analysis/core/actions/api.mathjs.org/schema.json)
   - **Política de privacidad:** [privacy.html](Relational-Analysis/core/actions/privacy.html)

---

### **Uso**

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/codevaried/codevaried-gpt-custom.git
   cd codevaried-gpt-custom
   ```
2. Dirígete a la carpeta del agente que deseas implementar, por ejemplo:
   ```bash
   cd Relational-Analysis
   ```
3. Sigue las instrucciones específicas en el archivo `README.md` del agente.

---

### **Contribuciones**

¡Este repositorio es de código abierto! Si deseas contribuir:

1. Haz un fork del repositorio.
2. Crea una rama nueva:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Haz tus cambios y súbelos:
   ```bash
   git add .
   git commit -m "Agrega nueva funcionalidad"
   git push origin feature/nueva-funcionalidad
   ```
4. Abre un Pull Request y describe tus cambios.

---

### **Licencia**

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y compartirlo libremente. Consulta el archivo `LICENSE` para más detalles.

---

### **Contacto**

Si tienes preguntas, sugerencias o encuentras algún problema, contacta en:  
📧 [codevaried@gmail.com](mailto:codevaried@gmail.com)

---

### **Notas**

- Este repositorio está en constante evolución. Se agregarán más agentes personalizados en el futuro.
- Si tienes ideas para nuevos agentes o mejoras, ¡déjanos saber en un issue o contribuye directamente!

---

### **Vista Previa**

Puedes consultar el repositorio en: [codevaried-gpt-custom](https://github.com/codevaried/codevaried-gpt-custom)
