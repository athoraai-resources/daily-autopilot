<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=E8740C&center=true&vCenter=true&width=600&lines=Daily+Autopilot+%F0%9F%9A%80;by+Athora+AI;Tus+tareas+diarias+en+piloto+autom%C3%A1tico" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/Claude_Code-Skill-E8740C?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTEyIDJDNi40OCAyIDIgNi40OCAyIDEyczQuNDggMTAgMTAgMTAgMTAtNC40OCAxMC0xMFMxNy41MiAyIDEyIDJ6bTAgMThjLTQuNDIgMC04LTMuNTgtOC04czMuNTgtOCA4LTggOCAzLjU4IDggOC0zLjU4IDgtOCA4eiIvPjwvc3ZnPg==&logoColor=white" />
<img src="https://img.shields.io/badge/Open_Source-Free-2ea44f?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Zero_Config-1_Command-blue?style=for-the-badge&logo=terminal&logoColor=white" />

<br/><br/>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" alt="Gear" width="80" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="80" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Calendar.png" alt="Calendar" width="80" />

<br/>

**Dile a Claude que hacer. Una vez. Se ejecuta solo. Todos los dias.**

[Instalar](#instalacion) · [Como funciona](#como-funciona) · [Comandos](#comandos) · [Athora AI](https://instagram.com/athoraai)

</div>

---

## El problema

<img align="right" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Tired%20Face.png" alt="Tired" width="60" />

Abres Claude todos los dias y le repites lo mismo:

- "Revisa mis workflows"
- "Envia los emails"
- "Genera contenido para Instagram"
- "Hazme el follow-up"

Todos. Los. Dias.

## La solucion

<img align="right" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Star-Struck.png" alt="Star" width="60" />

Lo configuras **una vez**. Claude lo ejecuta **siempre**.

```
/daily-autopilot setup
```

> Que tareas quieres automatizar?

```
1. A las 7am revisa que mis workflows esten activos
2. A las 9am envia 50 emails de outreach
3. A las 12pm genera ideas de contenido para Instagram
4. A las 3pm haz follow-up a leads sin respuesta
5. A las 5pm dame el reporte del dia
```

> Listo. 5 tareas guardadas. Se ejecutan automaticamente cada dia.

**No expiran. No se pierden. No tienes que repetirlas.**

---

## Instalacion

```bash
claude install athoraai-resources/daily-autopilot
```

Un comando. Ya esta.

---

## Como funciona

<div align="center">

```
Dia 1: Configuras tus tareas
         |
         v
   Se guardan en ~/.claude/daily-autopilot/tasks.json
         |
         v
Dia 2, 3, 4... infinito: Claude las ejecuta solo
         |
         v
   Si algo falla, te avisa. Si todo bien, te reporta.
```

</div>

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Backhand%20Index%20Pointing%20Down.png" alt="Point" width="30" /> Cada vez que abres Claude Code, un hook de SessionStart lee tus tareas y crea los cron jobs automaticamente.

---

## Comandos

| Comando | Que hace |
|---------|----------|
| `/daily-autopilot setup` | Configura tus tareas por primera vez |
| `/daily-autopilot list` | Muestra tus tareas activas |
| `/daily-autopilot add "tarea"` | Agrega una tarea nueva |
| `/daily-autopilot remove 3` | Quita la tarea #3 |
| `/daily-autopilot run` | Ejecuta todo ahora (sin esperar horario) |

---

## Ejemplo real

```bash
> /daily-autopilot list
```

| # | Hora | Tarea | Estado |
|---|------|-------|--------|
| 1 | 7:00 AM | Revisar workflows n8n | Activa |
| 2 | 9:00 AM | Enviar 50 emails de outreach | Activa |
| 3 | 12:00 PM | Generar ideas de contenido IG | Activa |
| 4 | 3:00 PM | Follow-up a leads sin respuesta | Activa |
| 5 | 5:00 PM | Reporte del dia | Activa |

<div align="center">
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Clapping%20Hands.png" alt="Clap" width="40" />
<br/>
<i>5 tareas. 0 veces repetidas. Todos los dias.</i>
</div>

---

## Que tipo de tareas puedo automatizar?

Cualquier cosa que Claude pueda ejecutar:

- Enviar emails (SMTP)
- Hacer requests HTTP (APIs, webhooks, n8n)
- Leer y escribir archivos (CSVs, JSONs, reportes)
- Generar contenido (captions, posts, ideas)
- Revisar y actualizar datos (CRMs, hojas de calculo)
- Ejecutar scripts (Python, Node, lo que tengas)

---

## Requisitos

- Claude Code instalado
- Eso. Nada mas.

---

<div align="center">

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Tools" width="60" />

### Creado por

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=E8740C&center=true&vCenter=true&width=400&lines=Athora+AI;Automatizaciones+con+IA;athoraaai.com" alt="Athora AI" />

**Automatizaciones con inteligencia artificial para empresas que quieren crecer de verdad.**

<a href="https://instagram.com/athoraai"><img src="https://img.shields.io/badge/Instagram-@athoraai-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
<a href="https://athoraaai.com"><img src="https://img.shields.io/badge/Web-athoraaai.com-E8740C?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
<a href="https://calendly.com/athoraaicol/30min"><img src="https://img.shields.io/badge/Asesoria_Gratis-30_min-2ea44f?style=for-the-badge&logo=calendly&logoColor=white" /></a>

</div>
