# 💬 Chatbot TalentoTech

Bienvenido a **Chatbot TalentoTech**. Este es un chatbot desarrollado para ofrecer respuestas rápidas y útiles en el área de la salud, centrado en preguntas frecuentes sobre temas médicos. Construido con Flask en el backend y Bootstrap en el frontend, el chatbot integra el modelo preentrenado DialoGPT de Microsoft para generar respuestas en lenguaje natural.

## 🎯 Objetivo del Proyecto
El objetivo de este chatbot es proporcionar una herramienta interactiva que asista a usuarios con dudas relacionadas a la salud. Puede ser integrado en sitios web de **EPS/IPS**, hospitales, o clínicas para ayudar a los pacientes con información relacionada a temas como el cáncer de mama, cuello uterino, o estómago, entre otros.


## 🛠️ Tecnologías Utilizadas

### Backend
- **[Flask](https://flask.palletsprojects.com/)**: Micro-framework para aplicaciones web en Python.
- **[DialoGPT](https://huggingface.co/microsoft/DialoGPT-medium)**: Modelo de lenguaje natural preentrenado.


### Frontend
- **HTML5**
- **CSS3**
- ***[Bootstrap](https://getbootstrap.com/)**: Framework de diseño responsive.
- **JavaScript**: Manejo de la interacción del chat.
jQuery: Para facilitar las peticiones AJAX.


## 🚀 Características

- **Conversación en Tiempo Real**: El chatbot responde a las preguntas de los usuarios de forma interactiva.
- **Interfaz Atractiva**: Un diseño moderno, limpio y fácil de usar, potenciado por Bootstrap.
- **Soporte en Salud**: Ideal para EPS/IPS, hospitales o clínicas para ayudar a resolver consultas rápidas.
- **Modelo NLP**: Utiliza el modelo preentrenado **DialoGPT** de Microsoft para generar respuestas precisas en lenguaje natural.


## 🌟 Funcionalidades

- **Envío y recepción de mensajes**: El usuario puede enviar un mensaje, y el chatbot responderá de manera coherente.
- **Mensajes del usuario y bot**: Los mensajes del usuario aparecen alineados a la derecha y los del bot a la izquierda.
- **Diseño Responsive**: Compatible con todos los tamaños de pantalla.

---

## 📸 Capturas de Pantalla

**Pantalla principal del chatbot**  
![Chatbot Screenshot](https://i.ibb.co/sgFtnK4/chatbot.png)

---

## ⚙️ Instalación y Configuración

### 1. Clonar el Repositorio

```bash
git clone https://github.com/jorgejc/chatbot-taletotech.git
cd chatbot-talento-tech

```

### 3. Configuración del proyecto

1. Crea un archivo `.env` en la raíz del proyecto.
2. Añade tus credenciales de AWS al archivo `.env` en el siguiente formato:

   ```dotenv
   AWS_ACCESS_KEY_ID=TU_ACCESS_KEY_ID
   AWS_SECRET_ACCESS_KEY=TU_SECRET_ACCESS_KEY
   AWS_REGION=us-east-1  # O la región que estés usando


### 4. Instalar dependencias

```bash
pip install -r requirements.txt
```


### 5. **Protección adicional**
Aunque tu archivo `.env` no se sube al repositorio (si está en `.gitignore`), siempre es bueno advertir a los usuarios que protejan sus credenciales y no las compartan públicamente.

### 6. **Uso de servicios de gestión de secretos**
En proyectos más avanzados o de producción, es recomendable usar un servicio de gestión de secretos como **AWS Secrets Manager** o **HashiCorp Vault** para almacenar y acceder a las credenciales de forma segura en lugar de depender de archivos `.env`.


### Ejecutar aplicación
```bash
python app.py
```

Accede a la aplicación en tu navegador en 
http://127.0.0.1:5000.
