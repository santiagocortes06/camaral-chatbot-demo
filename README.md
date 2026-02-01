# camaral-chatbot-demo
# Camaral Chatbot Demo

Este proyecto demuestra un chatbot conversacional para Camaral enfocado en ventas y soporte, utilizando inteligencia artificial y una arquitectura escalable.

## Arquitectura
- Frontend: Lovable
- Backend: n8n Cloud
- LLM: OpenAI
- Knowledge Base: GitHub (markdown dinámico)

## Flujo
1. El usuario interactúa con el chatbot.
2. El mensaje se envía a n8n vía webhook.
3. n8n consulta la base de conocimiento en GitHub.
4. El LLM genera una respuesta contextualizada.
5. La respuesta se devuelve al frontend.

## Beneficios
- Información siempre actualizada.
- Fácil escalabilidad.
- Separación clara entre lógica, contenido y presentación.

## Demo
El chatbot responde preguntas sobre Camaral, casos de uso, precios y seguridad, y puede guiar al usuario a agendar una demo.
