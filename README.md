# English Coffee Time - CAT Test

Un sistema completo de evaluación de inglés mediante un test adaptativo de 45 minutos (CAT - Computer Adaptive Testing) basado en el Marco Común Europeo de Referencia (MCER).

## 🎯 Características

- **Test Adaptativo**: El test se ajusta automáticamente según el desempeño del estudiante
- **4 Fases de Evaluación**: Conversación, Escenarios, Producción Escrita y Comprensión
- **Niveles MCER**: Evalúa desde A1 hasta C2
- **Dashboard para Profesores**: Panel completo para ver resultados de estudiantes
- **Planes de Estudio Personalizados**: Temas recomendados según nivel y debilidades
- **Reportes en PDF**: Descarga de reportes detallados para estudiantes
- **Exportación de Datos**: Exporta temas de estudio en CSV para planificación de clase

## 🚀 Tecnologías

- HTML5
- CSS3 (con variables de tema)
- JavaScript Vanilla
- jsPDF (para generar reportes)
- Vercel (para hosting)

## 📁 Estructura del Proyecto

```
english-coffee-time-cat/
├── index.html           # Página de inicio
├── test.html            # Página del test CAT
├── dashboard.html       # Panel de resultados para profesores
├── styles.css           # Estilos globales
├── js/
│   ├── test.js          # Lógica del test
│   └── dashboard.js     # Lógica del dashboard
├── README.md            # Este archivo
├── .gitignore           # Archivos a ignorar en Git
└── package.json         # Información del proyecto
```

## 💻 Instalación Local

1. **Clonar el repositorio**
```bash
git clone https://github.com/felixgarcia/english-coffee-time-cat.git
cd english-coffee-time-cat
```

2. **Ejecutar localmente**
Opción A: Con Python
```bash
python -m http.server 8000
```

Opción B: Con Node.js (instalando http-server)
```bash
npm install -g http-server
http-server
```

Opción C: Con Live Server en VS Code
- Instala la extensión "Live Server"
- Click derecho en index.html → "Open with Live Server"

3. **Acceder a la aplicación**
```
http://localhost:8000
```

## 🌐 Desplegar en Vercel

### Opción 1: Conectar GitHub a Vercel (Recomendado)

1. **Pushear a GitHub**
```bash
git remote add origin https://github.com/TU_USUARIO/english-coffee-time-cat.git
git branch -M main
git push -u origin main
```

2. **Conectar en Vercel**
- Ve a [vercel.com](https://vercel.com)
- Click en "New Project"
- Selecciona tu repositorio de GitHub
- Vercel detectará automáticamente que es un proyecto HTML
- Click en "Deploy"

3. **Tu URL pública**
```
https://english-coffee-time-cat.vercel.app
```

### Opción 2: Deploy manual desde CLI

1. **Instalar Vercel CLI**
```bash
npm install -g vercel
```

2. **Deploy**
```bash
vercel
```

3. **Seguir las instrucciones en pantalla**

## 📖 Uso

### Para Estudiantes

1. Ingresa a la página principal
2. Haz click en "Comenzar Test"
3. Completa el formulario con tu nombre y correo
4. Responde las 15 preguntas en 45 minutos
5. Obtén tu reporte final con tu nivel MCER
6. Descarga el PDF con tu plan de estudio personalizado

### Para Profesores

1. Ingresa a "Ver Dashboard"
2. Ve la lista de todos tus estudiantes y sus resultados
3. Haz click en un estudiante para ver detalles
4. Descarga el reporte en PDF
5. Exporta los temas de estudio en CSV para planificar tu clase

## 📊 Cómo funciona el Test

### Adaptación de Nivel
- El test comienza en B1
- Si respondes bien (>75%): Sube un nivel
- Si respondes mal (<40%): Baja un nivel
- Se ajusta dinámicamente a tus respuestas

### Evaluación
Cada respuesta se evalúa considerando:
- Longitud y detalle de la respuesta
- Uso de vocabulario complejo
- Complejidad gramatical
- Coherencia y fluidez

### Fases del Test

**Fase 1: Conversación (Preguntas 1-4)**
Preguntas sobre la vida cotidiana, hobbies, experiencias

**Fase 2: Escenarios (Preguntas 5-8)**
Situaciones reales donde debes responder apropiadamente

**Fase 3: Producción Escrita (Preguntas 9-12)**
Redacción de textos formales y cortos

**Fase 4: Comprensión (Preguntas 13-15)**
Análisis de textos e identificación de ideas principales

## 📝 Temas por Nivel

El sistema genera automáticamente planes de estudio según el nivel MCER:

- **A1**: Vocabulario básico, verbo "to be", pronunciación
- **A2**: Vocabulario intermedio, presente continuo, viajes
- **B1**: Vocabulario avanzado, modales, debates, correos formales
- **B2**: Expresiones idiomáticas, lenguaje académico
- **C1**: Sinónimos avanzados, estructuras complejas
- **C2**: Lenguaje literario, traducción profesional

## 🔮 Futuras Mejoras

- [ ] Conectar con Google Drive para almacenamiento automático
- [ ] Envío automático de reportes por email
- [ ] Autenticación de usuario (login/registro)
- [ ] Evaluación real con IA (integración Anthropic API)
- [ ] Sistema de recordatorio de práctica
- [ ] Gamificación y badges de progreso
- [ ] Análisis detallado de respuestas
- [ ] Recomendaciones de recursos por debilidad

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 👨‍💼 Autor

Desarrollado por **Felix Garcia** para English Coffee Time

- 🌍 Costa Rica
- 📧 Contacto: [felix@englishcoffeetime.com](mailto:felix@englishcoffeetime.com)
- 🔗 Website: [englishcoffeetime.com](https://englishcoffeetime.com)

## 📞 Soporte

Si tienes preguntas o problemas, abre un issue en el repositorio o contacta directamente.

## 🙏 Agradecimientos

- Marco Común Europeo de Referencia (MCER)
- jsPDF para generación de reportes
- Vercel por el hosting gratuito

---

**Última actualización**: Mayo 2025
