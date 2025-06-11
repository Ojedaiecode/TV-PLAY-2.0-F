# 📺 TV Play das Torcidas

Plataforma de streaming dedicada aos apaixonados por esportes, oferecendo conteúdo exclusivo e experiências únicas para torcedores.

## 🚀 Sobre o Projeto

A TV Play das Torcidas é uma plataforma inovadora que conecta torcedores através de conteúdo esportivo de qualidade. Com interface moderna e intuitiva, oferece streaming de conteúdo esportivo, highlights, análises e muito mais.

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript Puro
- Flask (Backend)
- Supabase (Banco de Dados)
- Netlify (Hospedagem Frontend)

## 📁 Estrutura do Projeto

```
TV-PLAY-2.0-F/
├── assets/
│   ├── img/
│   └── logos/
│
├── components-global/
│   ├── banner-global.html
│   ├── footer-global.html
│   └── navbar-global.html
│
├── componets-clone-login/
│   ├── clone.css
│   └── index-clone.html
│
├── css/
│   ├── main.css
│   ├── style.css
│   └── components-globals-css/
│       ├── banner-global.css
│       ├── footer-global.css
│       └── navbar-global.css
│
├── js/
│   ├── app.js               # Aplicação principal
│   ├── auth.js              # Sistema de autenticação e gestão de sessão de usuário
│   ├── config.js            # Configurações globais, URLs de API e endpoints
│   ├── home.js              # Lógica da página inicial
│   └── components-globais-js/
│       ├── banner-global.js
│       ├── footer-global.js
│       └── navbar-global.js
│
├── pages/
│   ├── filmes-gratis/
│   ├── series-comedia-assinates/
│   ├── canais-ao-vivo-assinates/
│   ├── series-comedia-gratis/
│   ├── series-desenho-gratis/
│   └── canais-ao-vivo-gratis/
│
├── index.html
├── home.html
└── README.md
```

## 🔧 Configuração do Ambiente

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/TV-PLAY-2.0-F.git
cd TV-PLAY-2.0-F
```

2. Abra o arquivo `index.html` em seu navegador ou use um servidor local.

## 🌐 Ambiente de Produção

- Frontend: [tvplaydastorcidas.com](https://tvplaydastorcidas.com)
- Backend: API Flask + Supabase

## 📦 Módulos Principais

- **Components Global**: Componentes reutilizáveis como navbar, footer e banner
- **Auth System** (`auth.js`): Sistema completo de autenticação integrado com Supabase
  - Login/Logout de usuários
  - Verificação de sessão
  - Controle de acesso a conteúdo premium
  - Integração com backend Flask
- **Config System** (`config.js`): Gerenciamento centralizado de configurações
  - URLs das APIs (Backend Flask)
  - Endpoints do Supabase
  - Configurações globais do sistema
  - Constantes e parâmetros do projeto
- **Streaming**: Sistema de reprodução de conteúdo
- **User Management**: Gestão de usuários e permissões

## 🔐 Variáveis de Ambiente

O projeto utiliza as seguintes variáveis de ambiente (configuradas no `auth.js`):
- API URLs
- Chaves de autenticação
- Configurações do Supabase

## 🤝 Contribuição

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença [MIT](LICENSE).

## 👥 Autores

- **Coronel Ojed** - *Idealizador e Desenvolvedor Principal*

## 📞 Contato

- Website: [tvplaydastorcidas.com](https://tvplaydastorcidas.com)
- GitHub: [seu-usuario](https://github.com/seu-usuario)

---
⌨️ com ❤️ por Coronel Ojed 😊
