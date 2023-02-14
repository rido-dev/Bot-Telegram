# Bot-Telegram
Script para enviar mensajes a través de un bot en la plataforma de mensajería telegram

En ciberseguridad podemos crear un BOT de Telegram que nos avise de los eventos que ocurren en una máquina.

Pasos a seguir para la creación del BOT:
  
  1 - Abrir un chat con **@BothFather** y escribir **/newbot** a continuación deberás elegir dos nombres para tu bot
  
  2 - Se te proporcionará un **TOKEN** que es indispensable para poder usar el bot
  
  3 - Abrir un chat con **@userinfobot** y escribir **/start** para conocer tu **ID** de telegram, también indispensable para usar el bot.
  
  4 - Para poder enviar el mensaje desde Linux deberemos tener instalado curl:
                        **sudo apt-get install curl**
                        
  5 - Si lo prefieres puedes crear un directorio en el que se encuentren los dos archivos **bot** y **bot.conf**
  
  6 - El contenido de **bot.conf**
      TOKEN=Aquí va tu TOKEN
      ID=Aquí va tu ID
