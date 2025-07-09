# <img align="center" height="60" width="80" src="https://raw.githubusercontent.com/Kakomo/Kakomo/main/discord.png"> Discord

Aplicativo estilo Discord!

## ✨ Fotos
### Chat Section on Android
<img src="assets/android_chat.png" alt="Chat section on Android" width="300"/>

### Server and Channel Section on Android
<img src="assets/android_main.png" alt="Server and Channel Section on Android" width="300"/>

### Chat Section on iOS
<img src="assets/iOS_chat.png" alt="Chat Section on iOS" width="300"/>

### Server and Channel Section on iOS
<img src="assets/iOS_main.png" alt="Server and Channel Section on iOS" width="300"/>

### Voice Call on macOS
<img src="assets/both_users_joined_mac.png" alt="Voice call on macOS" width="800"/>

### Video Call on macOS
<img src="assets/camera_on_mac.png" alt="Video call on macOS" width="800"/>

### Screen Share on macOS
<img src="assets/screen_share_mac.png" alt="Screen Share on macOS" width="800"/>

### Voice Call on Web
<img src="assets/both_users_joine_web.png" alt="Voice call on Web" width="800"/>

### Video Call on Web
<img src="assets/camera_on_web.png" alt="Video call on Web" width="800"/>

### Screen Share on Web
<img src="assets/screen_share_web.png" alt="Screen Share on Web" width="800"/>

## 🚀 Features
- Autenticação de Número de Telefone
- Bate-papo individual apenas com contatos
- Bate-papo em Grupo
- Compartilhamento de Texto, Imagem, GIF, Áudio (Gravação), Vídeo e Emoji
- Status visível apenas para contatos e desaparece após 24 horas
- Chamadas de Vídeo
- Status Online/Offline
- Mensagem Visualizada
- Respondendo a Mensagens
- Rolagem Automática em Novas Mensagens


## 🏗️  Arquitetura
Clean Architecture

### 1. **discord_flutter** - Frontend 
### 2. **discord_server** - Backend Server
### 3. **discord_client** - Generated Client

## Pacotes
- **Frontend**: Flutter, BLoC, Auto Route, LiveKit Client
- **Backend**: Serverpod, PostgreSQL, LiveKit Server
- **Real-time**: WebSockets, WebRTC
- **Code Generation**: Freezed, Build Runner

## Gerenciamento de Estado
BloC

