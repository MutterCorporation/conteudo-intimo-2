# IntimateContentPlatform

Uma plataforma moderna de conteúdo íntimo com design brutalist e recursos avançados de segurança.

## 🌟 Funcionalidades Principais

### 📱 Páginas Implementadas
- **Página Principal**: Landing page com design brutalist e paleta rosa
- **Autenticação**: Login, Signup e Signin com estilo consistente
- **Feed**: Visualização de conteúdo com interações
- **Chat**: Sistema de mensagens em tempo real
- **Match**: Videochamadas românticas
- **Random**: Chat aleatório com pessoas
- **Perfil**: Gerenciamento de conta do usuário
- **404**: Página de erro personalizada

### 🎨 Design e Estilo
- **Estilo Brutalist**: Design agressivo com formas geométricas
- **Paleta Rosa**: 9 tons de rosa consistentes em toda aplicação
- **Formas Temáticas**: Corações, cupidos, anéis, símbolos do infinito
- **Animações**: Heartbeat, shake, float, pulse e mais
- **Responsivo**: Adaptável para desktop e mobile

### 🔒 Recursos de Segurança Implementados

#### Proteção de Conteúdo
- **Anti-Screenshot**: Proteção limitada contra capturas de tela
- **Watermark**: Marca d'água invisível para proteção
- **Bloqueio de Seleção**: Prevenção de seleção de texto
- **Proteção de Imagens**: Desabilitação de drag & drop

#### Bloqueios de Sistema
- **DevTools Detection**: Detecção de ferramentas de desenvolvedor
- **Keyboard Shortcuts**: Bloqueio de F12, Ctrl+U, Ctrl+S, etc.
- **Context Menu**: Desabilitação do menu de contexto (botão direito)
- **Print Screen**: Bloqueio da tecla Print Screen

#### Headers de Segurança
- **X-Frame-Options**: DENY - Previne embedding
- **X-Content-Type-Options**: nosniff - Previne MIME sniffing
- **X-XSS-Protection**: Proteção contra XSS
- **Referrer-Policy**: no-referrer - Privacidade de referência
- **robots.txt**: noindex, nofollow - Não indexação

#### Proteções Adicionais
- **Viewport Lock**: Desabilitação de zoom manual
- **Visibility API**: Blur do conteúdo quando aba não está ativa
- **Console Warnings**: Mensagens de aviso no console
- **Auto-removal**: Remoção automática de overlays de aviso

### 🚀 Tecnologias Utilizadas

- **Next.js 14**: Framework React com App Router
- **TypeScript**: Tipagem estática
- **Tailwind CSS**: Styling utility-first
- **Styled JSX**: CSS-in-JS para componentes específicos
- **Lucide React**: Ícones modernos
- **Radix UI**: Componentes acessíveis
- **WebSocket**: Comunicação em tempo real (hooks preparados)

### 🎯 Paleta de Cores Rosa

css
:root {
  --misty-rose: #fadde1;
  --orchid-pink: #ffc4d6;
  --carnation-pink: #ffa6c1;
  --tickle-me-pink: #ff87ab;
  --french-rose: #ff5d8f;
  --bakermiller-pink: #ff97b7;
  --carnation-pink-2: #ffacc5;
  --pink: #ffcad4;
  --cherry-blossom-pink: #f4acb7;
}


### 🛡️ Como a Segurança Funciona

#### SecurityProvider
Componente global que envolve toda a aplicação e implementa:
- Event listeners para keyboard e mouse
- Detecção de DevTools
- Watermarks automáticos
- Estilos de proteção

#### Proteção Automática
O sistema utiliza mecanismos do lado do cliente para impedir a captura não autorizada de conteúdo e a inspeção do sistema, garantindo um ambiente seguro para os usuários.

## Começando

Primeiro, execute o servidor de desenvolvimento:

bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev


Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver o resultado.

## Aprenda Mais

Para aprender mais sobre Next.js, dê uma olhada nos seguintes recursos:

- [Documentação do Next.js](https://nextjs.org/docs) - aprenda sobre recursos e API do Next.js.
- [Aprenda Next.js](https://nextjs.org/learn) - um tutorial interativo do Next.js.
