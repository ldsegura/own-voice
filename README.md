# own-voice

Este proyecto tiene como objetivo permitir la traducción de audio en tiempo real durante videollamadas. El sistema captura el audio de la llamada, lo transcribe, lo traduce a otro idioma y luego lo convierte nuevamente en audio para ser reproducido en la llamada.

## Tecnologías Usadas

- **Python 3.x**: Lenguaje de programación principal.
- **Whisper**: Herramienta de transcripción de audio a texto.
- **Llama**: Modelo de traducción para convertir texto a otro idioma.
- **F5 TTS (Text-to-Speech)**: Conversión de texto a audio para enviar de vuelta en la videollamada.
- **VB-Audio Cable / Soundflower**: Para redirigir el audio de entrada y salida.


## Requisitos

- **Python 3.x** instalado.
- **pip** (gestor de paquetes de Python).
- Dependencias específicas que se instalarán mediante `pip install`.
