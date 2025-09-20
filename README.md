# Servidor AI

Este servidor corre en Express y usa la API de OpenAI.

### Pasos:
1. Sube este proyecto a Vercel, Render o Railway.
2. En la sección de **Secrets/Environment Variables** agrega:
   - `OPENAI_API_KEY` con tu clave de OpenAI.
   - `ADMOB_API_KEY` (si lo usas en tu app).
3. ¡Listo!

El endpoint principal será:  
```
POST /chat
Body: { "message": "hola" }
```
