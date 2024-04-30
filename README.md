# Fala de IA do Azure

Base de conhecimento: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html

O serviço de Fala de IA do Azure transcreve fala em texto e texto em fala audível. Você pode usar o AI Speech para criar um aplicativo que possa transcrever anotações de reuniões ou gerar texto a partir da gravação de entrevistas.

- 1 Em outra guia do navegador, abra o Azure AI Speech Studio, entrando com sua conta da Microsoft.
- 2 Selecione ```Configurações``` e ```Criar um recurso```.
- 3 Configure-o com as seguintes configurações:
Nome do novo recurso:```insira um nome exclusivo. ```
Assinatura:```sua assinatura do Azure.```
Região:```selecione uma região com suporte.```
Nível de preços:```FO gratuito (se disponível, caso contrário, selecione Standard S0).```
Grupo de recursos:```selecione ou crie um grupo de recursos com um nome exclusivo.```
- 4 Selecione ```Criar recurso```. Aguarde até que o recurso tenha sido criado e selecione ```Usar recurso```. A página Introdução à Fala é exibida.

# Explorar a conversão de voz em texto no Speech Studio

- 1 Selecione https://aka.ms/mslearn-speech-files para baixar speech.zip. Abra a pasta.
- 2 Na página Introdução à Fala, em Fala para texto, localize Conversão de fala em texto em tempo real.
Selecione ```Experimentar conversão de voz em texto em tempo real.```
![image](https://github.com/XlfelipeX/Fala_de_IA_do_Azure/assets/144381176/a75f74b3-7ad5-4f52-9285-0dee29295cc4)

- 3 Em Escolher arquivos de áudio, selecione ```Procurar arquivos``` e navegue até a pasta onde você salvou o arquivo. Selecione ```WhatAICanDo.m4a``` e, em seguida, ```Abrir```.
![image](https://github.com/XlfelipeX/Fala_de_IA_do_Azure/assets/144381176/64363326-2dcc-487d-9bbb-7788e963f782)

- 4 O serviço de Fala transcreve e exibe o texto em tempo real. Se você tiver áudio no computador, poderá ouvir a gravação enquanto o texto está sendo transcrito.
- 5 Revise a saída, que deve ter reconhecido e transcrito com sucesso o áudio em texto.
