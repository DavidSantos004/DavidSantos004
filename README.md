# David Santos

**Desarrollador Full-Stack · IA** · Bucaramanga, Colombia

[Portafolio con demos](https://davidsantos-eight.vercel.app) · [Hoja de vida](https://davidsantos-eight.vercel.app/David-Santos-HV.pdf) · [CV in English](https://davidsantos-eight.vercel.app/David-Santos-CV-EN.pdf)

Construyo productos completos: modelo de datos, API, interfaz y puesta en producción.
Trabajo en Industrias CTS, donde desarrollo las plataformas de ingeniería,
producción y monitoreo de un fabricante de tableros eléctricos.

Lo que más me interesa son los problemas que no se resuelven llamando a una librería:
sincronización de datos en vivo entre varios usuarios, rendimiento con miles de registros
en pantalla y motores de reglas que el usuario final pueda configurar por su cuenta.

---

### En qué trabajo

**Plataforma de gestión de flujos de trabajo**
Motor de automatizaciones, motor de fórmulas en Web Worker, sincronización en tiempo real
y visores de PDF/Excel/Word dentro del navegador. En uso diario por toda la empresa.
`React 19` `TypeScript` `NestJS` `Prisma` `PostgreSQL` `Redis` `Socket.IO` `GitHub Actions` `AWS ECS`

**HMI de monitoreo industrial**
Supervisión en tiempo real de dispositivos Modbus TCP/RTU, alarmas a nivel de bit,
visualización 3D de gabinetes eléctricos y despliegue en modo kiosko sobre Raspberry Pi.
`React` `Three.js` `Zustand` `Modbus` `Raspberry Pi`

**Plataforma de monitoreo IoT**
Telemetría con series de tiempo en InfluxDB y arquitectura de notificaciones sobre
AWS SQS + Lambda hacia WhatsApp y correo.
`NestJS` `InfluxDB` `AWS SQS` `AWS Lambda` `Mapbox GL`

**Gestión de pruebas FAT de tableros eléctricos**
Digitalización de formatos de inspección y ensayo, con trazabilidad por tablero.
`React` `NestJS` `PostgreSQL` `Docker`

> El código de estos proyectos es privado — es software interno de la empresa.
> En el [portafolio](https://davidsantos-eight.vercel.app) hay una demo funcional de cada uno.

---

### Cómo programo hoy

Con agentes de IA. Mi trabajo es diseñar el entorno en el que trabajan: instrucciones y
reglas por área del código, una skill que define qué significa "verificado", hooks con
sus propias pruebas que bloquean lo que no debe pasar, y varios agentes en paralelo con
un revisor por solicitud. Yo mido, decido y apruebo.
`Claude Code` `Orca` `hooks` `skills` `MCP`

La plantilla de ese entorno, sin nada de la empresa, está en [entorno-agentes](https://github.com/DavidSantos004/entorno-agentes): `CLAUDE.md` por capas, reglas por área, skill de verificación y hook de bloqueos con pruebas.

---

### IA dentro del producto

**[jarvis-os](https://github.com/DavidSantos004/jarvis-os)** · asistente de casa con modelo de lenguaje, en desarrollo.
El modelo nunca ejecuta nada: propone una acción estructurada (tool calling), el código la valida
contra un esquema y un orquestador decide según el riesgo; lo irreversible espera confirmación humana.
Dos proveedores detrás del mismo puerto: Ollama en local y la API de Anthropic.
`Python` `FastAPI` `Pydantic` `PostgreSQL` `API de Anthropic` `Ollama` `Home Assistant` `pytest`

---

### Tecnologías

**Día a día** — TypeScript · React · NestJS · Node.js · PostgreSQL · Prisma · Docker · Nginx
**Tiempo real y datos** — Socket.IO · InfluxDB · Three.js · Web Workers
**Nube y entrega** — AWS (SQS, Lambda, ECS, S3, SES) · GitHub Actions (CI/CD) · Docker Compose · Jest · Vitest
**Industrial** — Modbus TCP/RTU · MQTT · Raspberry Pi
**IA aplicada** — Tool calling · Salidas estructuradas · API de Anthropic · Ollama · Orquestación con confirmación humana
**También he trabajado con** — Java · Spring Boot · Python · PHP · MySQL

---

### Contacto

[LinkedIn](https://linkedin.com/in/davidsantos004) · [Portafolio](https://davidsantos-eight.vercel.app) · david.santoos004@gmail.com
