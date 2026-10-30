# 💙 greyce-dev

Portfólio de projetos web da **Greyce Rodrigues**. Cada projeto é uma aplicação completa em um único arquivo HTML, que roda direto no navegador, sem instalar nada.

🌐 **Veja online:** [https://greycerodriguesbr-glitch.github.io/greyce-dev/](https://greycerodriguesbr-glitch.github.io/greyce-dev/)

| Projeto | O que faz | Testar |
|---|---|---|
| 🏥 **SaúdePerto** | App de saúde com assistente de IA para picadas e mordidas, busca de hospitais, consultas, remédios e vacinas | [▶ Abrir](https://greycerodriguesbr-glitch.github.io/greyce-dev/saudeperto/) |
| 📸 **FotoEvento** | Fotos impressas em eventos: QR Code único por convidado, confirmação por celular e código de retirada | [▶ Abrir](https://greycerodriguesbr-glitch.github.io/greyce-dev/fotoevento/) |

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
- 🆘 **Emergência**: números úteis como 192 (SAMU) e 193 (Bombeiros) e ficha médica para socorristas
- 🌙 Modo escuro, layout responsivo para celular e preocupação com a **LGPD**

### Como usar

Acesse [o app online](https://greycerodriguesbr-glitch.github.io/greyce-dev/saudeperto/) ou abra `saudeperto/index.html` no navegador. Na tela de login, clique em **"Usar CPF de teste"** para entrar com dados de demonstração.

---

## 📸 FotoEvento

> *Transforme cada momento em memórias especiais.*

Plataforma para fotógrafos e organizadores de casamentos, aniversários e formaturas. Cada convidado recebe um **QR Code único**, envia sua melhor foto pelo celular e retira a foto impressa no balcão com um **código de retirada** gerado na hora.

### Como funciona

1. **O organizador cria uma conta** e cadastra o evento
2. **Cadastra os convidados** com nome e celular, e cada um ganha um QR Code único
3. **O convidado escaneia o QR**, confirma o próprio celular e envia a foto
4. **Na hora, é gerado um código de retirada** de 6 números, pessoal e de uso único
5. **No balcão**, o organizador digita o código, confere a foto e confirma a entrega

### Funcionalidades

- 🔐 **Contas de organizador**: criar conta, entrar e sair, com senha protegida por hash e aceite da LGPD
- 🎪 **Vários eventos por conta**, com evento ativo e indicadores de andamento
- 👥 **Convidados com celular**, busca por nome ou número e QR Code único e intransferível
- 📱 **Confirmação de identidade**: o convidado só envia a foto depois de confirmar o celular cadastrado
- 🎟️ **Código de retirada** gerado no envio e **tela de retirada** para validar e marcar a entrega
- 🖨️ **Impressão do QR Code** em formato de cartão, pronto para mesa ou convite
- 🖼️ **Galeria de fotos** com status (aguardando, pronta para retirar, retirada) e download
- 📉 Fotos reduzidas automaticamente para carregar rápido e caber no armazenamento
- 📲 Layout responsivo para celular, sem bibliotecas além do gerador de QR Code

### Como usar

Acesse [o app online](https://greycerodriguesbr-glitch.github.io/greyce-dev/fotoevento/) ou abra `fotoevento/index.html` no navegador. Crie sua conta ou clique em **"Entrar com a conta de demonstração"**, que já vem com um evento e convidados de exemplo.

> Os dados ficam salvos no próprio navegador. Para testar o fluxo completo, use o botão **Testar** no QR Code de um convidado: ele abre a página do convidado na mesma máquina.

---

## 🛠️ Tecnologias

- HTML5, CSS3 e JavaScript puro (sem frameworks)
- Design responsivo e acessível
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) para gerar os QR Codes do FotoEvento

## 🚧 Próximos passos

- SaúdePerto: conectar a uma base real de estabelecimentos de saúde e salvar os dados do usuário em um servidor
- FotoEvento: servidor com banco de dados e armazenamento em nuvem, para o QR Code funcionar no celular de qualquer convidado, e envio do código de retirada por SMS ou WhatsApp

---

Feito com 💙 por **Greyce Rodrigues**
