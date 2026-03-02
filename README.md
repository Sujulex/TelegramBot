# 🤖 Telegram Bot con Spring Boot

Este es un bot de Telegram funcional desarrollado como un proyecto educativo utilizando **Java 21** y **Spring Boot 3**. El bot utiliza la técnica de *Long Polling* para recibir y responder mensajes de forma automática.

## 🚀 Características
* **Respuesta Automática:** El bot reconoce mensajes de texto y responde con un agradecimiento personalizado.
* **Configuración Segura:** Utiliza anotaciones `@Value` para gestionar credenciales desde archivos de propiedades.
* **Arquitectura Limpia:** Estructurado en paquetes de configuración y servicios para facilitar su escalabilidad.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Java 21
* **Framework:** Spring Boot 3.2.5
* **Librería:** [TelegramBots](https://github.com/rubenlagus/TelegramBots)
* **Gestor de dependencias:** Maven

## 📋 Requisitos Previos
1. Tener instalado **Java 21** o superior.
2. Un IDE (recomendado **Spring Tool Suite** o Eclipse).
3. Un **Token de API** proporcionado por [@BotFather](https://t.me/botfather) en Telegram.

## ⚙️ Configuración
Para que el bot funcione, debes configurar tus credenciales en el archivo `src/main/resources/application.properties`:

```properties
telegram.bot.username=TuNombreDeBot
telegram.bot.token=TuTokenDeTelegram
