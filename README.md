🚀 AnyConvert Pro - Multi-Tool Web
AnyConvert Pro es una plataforma web "todo en uno" diseñada para facilitar la conversión de documentos, imágenes y archivos multimedia directamente desde el navegador. El proyecto nació para resolver problemas comunes de compatibilidad y seguridad al procesar archivos pesados localmente, migrando el procesamiento crítico a una infraestructura basada en la nube.

✨ Características Principales
📄 Conversión de Documentos: Transforma archivos de Word (.docx) a PDF y viceversa de forma instantánea.

🎬 Procesador Media Pro: Extrae audio de videos o convierte formatos (MP3, WAV, MP4, AVI) utilizando la potencia de Cloudinary.

🎶 Optimizado para Audio CD: Genera archivos WAV con calidad profesional, ideales para grabar discos físicos bajo el estándar Red Book.

🖼️ Imagen Express: Conversión ultrarrápida de formatos de imagen (JPG, PNG, WebP) procesada localmente mediante la API de Canvas para mayor privacidad.

📦 Subida Múltiple: Soporte para seleccionar y procesar varios archivos simultáneamente, creando una cola de descargas organizada.

🛠️ Tecnologías Utilizadas
Frontend: HTML5, JavaScript (ES6+), Tailwind CSS.

Backend Services: Cloudinary API para procesamiento de documentos y multimedia.

Iconografía: Font Awesome 6.0.

🚀 Instalación y Despliegue
Sigue estos pasos para poner en marcha tu propia instancia de AnyConvert Pro:

Clonar el repositorio:

Bash

git clone https://github.com/tu-usuario/anyconvert-pro.git
Configurar Cloudinary:

Crea una cuenta gratuita en Cloudinary.

En el código de index.html, actualiza la constante CLOUD_NAME con tu identificador de nube (ej: diencefre).

Crea un Upload Preset en modo Unsigned llamado anyconvert_preset en los ajustes de subida de Cloudinary.

Ejecutar:

Abre index.html mediante un servidor local (ej: Live Server en VS Code) para evitar restricciones de seguridad del navegador.

🧪 Desafíos Superados
Este proyecto evolucionó desde una implementación local con FFmpeg.wasm que presentaba errores de memoria y seguridad (SharedArrayBuffer, proxy_main) hacia una arquitectura híbrida nube/cliente. Este cambio garantiza que la aplicación funcione en cualquier navegador moderno y dispositivo móvil sin configuraciones de servidor complejas.
