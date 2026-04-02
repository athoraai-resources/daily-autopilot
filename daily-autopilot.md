# Daily Autopilot — by Athora AI

Configura tareas que Claude ejecuta automaticamente todos los dias. Sin repetir instrucciones. Sin expiracion.

## Que hace

Al ejecutar `/daily-autopilot` por primera vez, te pregunta:

> Que tareas quieres que ejecute todos los dias?

Guardas tus tareas una sola vez. Desde ese momento, cada vez que abras Claude Code, las ejecuta automaticamente sin que tengas que pedirlo.

## Como funciona

1. **Configura una vez** — Describe las tareas que quieres automatizar (enviar emails, revisar datos, generar reportes, actualizar archivos, lo que sea)
2. **Elige horarios** — Asigna a cada tarea la hora en que quieres que se ejecute
3. **Olvidate** — Claude las ejecuta solas cada dia. Si algo falla, te avisa.

## Instalacion

```bash
claude install athoraai/daily-autopilot
```

## Uso

```bash
# Primera vez: configura tus tareas
/daily-autopilot setup

# Ver tareas activas
/daily-autopilot list

# Agregar nueva tarea
/daily-autopilot add "Enviar reporte de ventas por email a las 9am"

# Quitar una tarea
/daily-autopilot remove 3

# Ejecutar todo ahora (sin esperar horario)
/daily-autopilot run
```

## Ejemplo real

```
/daily-autopilot setup
```

> Que tareas quieres automatizar?

```
1. A las 7am revisa que mis 5 workflows de n8n esten activos
2. A las 9am envia 50 emails de outreach a leads nuevos del CRM
3. A las 12pm genera ideas de contenido para Instagram basado en trends
4. A las 3pm haz follow-up a los leads que no respondieron
5. A las 5pm dame un reporte del dia
```

> Listo. 5 tareas guardadas. Se ejecutan automaticamente cada dia.
> Usa /daily-autopilot list para verlas.

## Donde se guardan las tareas

Las tareas se guardan en `~/.claude/daily-autopilot/tasks.json`. No se pierden entre sesiones. No expiran. Se ejecutan cada vez que inicias Claude Code a traves de un hook de SessionStart.

## Requisitos

- Claude Code instalado
- Las tareas deben describir acciones que Claude pueda ejecutar (leer archivos, enviar emails, hacer requests HTTP, generar contenido, etc.)

## Creado por

**Athora AI** — Automatizaciones con inteligencia artificial para empresas que quieren crecer de verdad.

Instagram: [@athoraai](https://instagram.com/athoraai)
Web: [athoraaai.com](https://athoraaai.com)
