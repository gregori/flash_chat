# Flash Chat

Um aplicativo simples de chat síncrono, escrito em Flutter.

## Equipe
* Rodrigo Gregori

## Funcionalidades

* Chat síncrono, com apenas uma sala, entre várias pessoas
* Autenticação de usuário por email e senha (via Firebase)
* Registro de usuários por email e senha
* Chat sincronizado (pode ser acessado de qualquer dispositivo), através de tabelas firebase

## Pacotes utilizados

| Pacote | Versão | Função |
|:------:|:------:|--------|
| animated_text_kit | 4.2.1 | Animação para o ícone de raio do login e registro |
| firebase_core | 1.8.0 | Pacote básico para utilizar o firebase |
| firebase_auth | 3.1.4 | Pacote para habilitar a autenticação do firebase |
| cloud_firestore | 2.5.4 | Pacote para o uso do firebase cloud firestore |
| modal_progress_hud_nsn | 0.1.0-nullsafety-1 | Mostra um indicador de carregamento modal (sobre a tela |

## Informações para execução

1. Crie um projeto na [console firebase](https://console.firebase.google.com/)
2. Habilite uma database cloudfirestore. 
3. Habilite autenticação por email e senha.
4. Baixe o arquivo google-services.json de seu projeto firebase e o copie dentro do diretório `android/app` do projeto flutter.
5. Execute em um celular ou imagem Android com Google Play habilitada.
