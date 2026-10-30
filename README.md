# 💙 greyce-dev

Portfólio de projetos web da **Greyce Rodrigues**. Cada projeto é uma aplicação completa em um único arquivo HTML, que roda direto no navegador, sem instalar nada.

| Projeto | O que faz | Pasta |
|---|---|---|
| 🏥 **SaúdePerto** | App de saúde com assistente de IA para picadas e mordidas, busca de hospitais, consultas, remédios e vacinas | [`saudeperto/`](saudeperto/) |
| 📸 **FotoEvento** | Coleta de fotos de eventos: cada convidado recebe um QR Code e envia uma foto | [`fotoevento/`](fotoevento/) |

---

## 🏥 SaúdePerto

> *Sua saúde mais perto de você.*

Um app que reúne em um só lugar tudo o que a pessoa precisa para cuidar da saúde, pensado para o dia a dia de quem usa o SUS e também a rede particular.

### Funcionalidades

- 🤖 **Assistente com IA para picadas e mordidas**: a pessoa escolhe o animal e os sintomas, e a IA indica a gravidade, o que fazer e o que não fazer, o soro ou remédio adequado e o melhor lugar para ser atendida
- 🗺️ **Busca de atendimento**: hospitais, clínicas, UBS, UPAs 24h e farmácias, públicos e particulares, com filtros
- 🧭 **Onde ir?**: guia rápido que indica, pelos sintomas, se o caso é para UBS, UPA ou 192
- 📅 **Consultas**: organização de consultas, exames e retornos
- 💊 **Remédios**: lembretes diários com acompanhamento do progresso
- 💉 **Carteira de vacinas** digital
- ⚠️ **Alertas na região**: doenças em circulação, sintomas e prevenção
- 🆘 **Emergência**: números úteis (192, 193, 190) e ficha médica para socorristas
- 🌙 Modo escuro, layout responsivo para celular e preocupação com a **LGPD**

### Como usar

Abra `saudeperto/index.html` no navegador. Na tela de login, clique em **"Usar CPF de teste"** para entrar com dados de demonstração.

---

## 📸 FotoEvento

Ideal para casamentos, aniversários e formaturas: o organizador cadastra os convidados, gera um **QR Code único** para cada um, e o convidado escaneia e envia sua melhor foto do evento. Cada QR Code só pode ser usado **uma vez**.

### Funcionalidades

- 📊 **Dashboard** com total de eventos, convidados, fotos recebidas e pendentes
- 🎪 **Cadastro de eventos** com nome, data e local
- 👥 **Lista de presença** com busca e status de cada convidado
- 📱 **QR Code por convidado**, pronto para imprimir
- 📷 **Página de envio** para o convidado, com pré-visualização e limite de 10 MB
- ⬇️ **Galeria de fotos recebidas** com download

### Como usar

Abra `fotoevento/index.html` no navegador e entre com o usuário de demonstração **admin** / **1234**.

---

## 🛠️ Tecnologias

- HTML5, CSS3 e JavaScript puro (sem frameworks)
- Design responsivo e acessível
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) para gerar os QR Codes do FotoEvento

## 🚧 Próximos passos

- SaúdePerto: conectar a uma base real de estabelecimentos de saúde e salvar os dados do usuário em um servidor
- FotoEvento: guardar as fotos na nuvem e bloquear o QR Code no servidor, não só no navegador

---

Feito com 💙 por **Greyce Rodrigues**
