# Mi intención inicial

## Proceso o problema que me gustaría explorar

- En mi rol soy intermediaria ("embudo") entre clientes y tres frentes:
  administración, mentores y equipo interno.
- Muchas tareas quedan en pausa esperando información de una de las partes.
  Cuando llega, tengo que interrumpir lo que hago, retomar el contexto y
  pasarla al otro lado. Cada interrupción me cuesta enfoque (TDAH) y se
  pierde tiempo entre que llega la información y yo la muevo.
- Ejemplo recurrente: coordinar una reunión esperando la disponibilidad de
  una o más personas; cuando alguien confirma horario, alguien (yo) tiene
  que crear la invitación.

## Qué resultado me gustaría obtener

- Un agente que revise periódicamente mis pendientes de coordinación
  (las tarjetas con mi nombre en el Kanban de equipo en Notion) y detecte
  cuándo ya llegó lo que se esperaba (por correo o Slack).
- Cuando eso pase, que dispare la salida correspondiente:
  - reenviar un correo/documento a quien corresponda;
  - crear la reunión en Google Calendar con las personas invitadas;
  - o crear un bloque/recordatorio para mí cuando la tarea requiera mi trabajo.
- Las salidas de calendario pasarían por Calendarizer (otra herramienta de IA
  que estoy desarrollando y que convierte pendientes en bloques de Google Calendar).
- Autonomía gradual: al inicio el agente propone y yo apruebo cada acción
  (human-in-the-loop); con el tiempo, las acciones de rutina se ejecutan solas
  y solo me notifica.
- Fuera de alcance: WhatsApp y llamadas (son personales o poco frecuentes).

## Qué herramienta usaré primero

- Claude Code, conectado a Gmail, Slack, Google Calendar y Notion.

## Qué fallback usaré si la herramienta falla

- Cowork con los mismos conectores; si tampoco está disponible, un registro
  manual en Notion de "esperando a / qué llegó / qué sigue" para no perder el hilo.

No incluye datos personales, secretos ni información de clientes.