# Assistente_de_Voz_Multi_Idiomas_Com_Whisper_e_ChatGPT
Conversando Por Voz Com o ChatGPT Utilizando Whisper (OpenAI) e Python
Sistema que combina as tecnologias de Speech-to-Text (voz para texto) e Text-to-Speech (texto para voz) para proporcionar uma conversa multi-idiomas por voz com o ChatGPT. 
O código é desenvolvido em 4 etapas:
### 1 - Gravação de Áudio Com Python e JavaScript
Captura-se o áudio do usuário diretamente no navegador por meio da Web API MediaDevices. O arquivo é acessado usando python.
### 2 - Reconhecimento de Fala com Whisper (OpenAI) 
É realizada a transcrição do áudio para texto
### 3 - Integração com a API do ChatGPT 
Aqui é onde será realizada a troca de textos com o ChatGPT. Utiliza-se a API da OpenAI. É enviada transcrição do whisper da etapa 2 e o retorno será a resposta do ChatGPT.
### 4 - Sintetizando a Resposta do ChatGPT Como Voz (gTTS) 
Por fim, usa-se o gTTS, biblioteca em Python que utiliza a API de Text-to-Speech do Google, sintetizando o texto em voz no idioma escolhido. Assim, a resposta do ChatGPT é entrege ao usuário por meio de voz. 
<br><br><br><br>
> Desenvolvido no **Coding the Future**, da **DIO**.
