# 🔗 DevLinks

<p align="center">
  Uma página de links personalizável com alternância entre tema claro e escuro, perfeita para centralizar todos os seus links importantes em um só lugar.
</p>

<div align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-funcionalidades">Funcionalidades</a> •
  <a href="#-tecnologias">Tecnologias</a> •
  <a href="#-como-usar">Como usar</a> •
  <a href="#-estrutura-do-projeto">Estrutura</a> •
  <a href="#-customização">Customização</a> •
  <a href="#-layout">Layout</a> •
  <a href="#-licença">Licença</a>
</div>

<br>

---

## 📋 Sobre o Projeto

O **DevLinks** é um agregador de links responsivo que funciona como uma página de perfil pessoal, similar ao Linktree. O projeto foi desenvolvido como parte do programa gratuito da Rocketseat e apresenta uma interface moderna e elegante com alternância entre temas claro e escuro.

### 🎯 Objetivo

Criar uma página centralizada onde você pode compartilhar todos os seus links importantes de forma organizada e visualmente atrativa, ideal para usar na bio de redes sociais.

---

## ✨ Funcionalidades

- 🌓 **Alternância de Tema**: Troca entre modo claro e escuro com animação suave
- 📱 **Design Responsivo**: Adapta-se perfeitamente a diferentes tamanhos de tela
- 🔗 **Links Personalizáveis**: Adicione e organize seus links principais
- 📸 **Foto de Perfil**: Espaço para sua foto ou avatar
- 🌐 **Redes Sociais**: Ícones diretos para suas redes sociais
- 🎨 **Efeitos Visuais**: Hover effects e transições suaves
- ⚡ **Performance**: Carregamento rápido e otimizado

---

## 🚀 Tecnologias

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

### Frontend
- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) **HTML5**: Estrutura semântica da página
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) **CSS3**: Estilização avançada e responsividade
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) **JavaScript**: Funcionalidade de alternância de tema

### Recursos Externos
- **Google Fonts**: Fonte Inter para tipografia
- **Ionicons**: Ícones das redes sociais
- **CSS Variables**: Para gerenciamento dinâmico de temas

### Ferramentas
- ![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat&logo=figma&logoColor=white) **Figma**: Design e prototipação
- ![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white) **Git**: Controle de versão

---

## 🔧 Como Usar

### Pré-requisitos
- Navegador web moderno
- Editor de código (VS Code recomendado)

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/devlinks.git
   ```

2. **Acesse o diretório**
   ```bash
   cd devlinks
   ```

3. **Abra o projeto**
   - Abra o arquivo `index.html` em seu navegador
   - Ou use a extensão Live Server no VS Code

### Uso Local
- Abra o arquivo `index.html` diretamente no navegador
- Teste a funcionalidade de alternância de tema
- Visualize a responsividade redimensionando a janela

### Deploy
O projeto pode ser facilmente implantado em:
- GitHub Pages
- Netlify
- Vercel
- Qualquer servidor web estático

---

## 📁 Estrutura do Projeto

```
devlinks/
├── 📄 index.html          # Estrutura principal da página
├── 🎨 style.css           # Estilos e responsividade
├── ⚡ script.js          # Funcionalidade JavaScript
├── 📖 README.md          # Documentação do projeto
├── 📁 assets/            # Recursos visuais
│   ├── 🖼️ avatar.png       # Foto de perfil
│   ├── 🌄 bg-desktop.jpg   # Background desktop (tema escuro)
│   ├── ☀️ bg-desktop-light.jpg # Background desktop (tema claro)
│   ├── 🌄 bg-mobile.jpg    # Background mobile (tema escuro)
│   ├── ☀️ bg-mobile-light.jpg # Background mobile (tema claro)
│   ├── 🌙 moon-stars.svg   # Ícone do modo escuro
│   └── ☀️ sun.svg          # Ícone do modo claro
└── 📁 .vscode/           # Configurações do VS Code
    ├── extensions.json   # Extensões recomendadas
    └── settings.json    # Configurações do workspace
```

### Descrição dos Arquivos

#### `index.html`
- Estrutura HTML semântica
- Links para redes sociais e portfólio
- Integração com Ionicons para ícones
- Profile com foto e nome de usuário

#### `style.css`
- CSS Variables para alternância de temas
- Design responsivo com media queries
- Animações e transições suaves
- Efeitos hover interativos

#### `script.js`
- Função `toggleMode()` para alternância de tema
- Manipulação do DOM
- Lógica para troca de classes CSS

---

## 🎨 Customização

### Alterando Informações Pessoais

1. **Foto de Perfil**
   ```html
   <img src="./assets/avatar.png" alt="Sua foto" />
   ```

2. **Nome de Usuário**
   ```html
   <p>@seu_usuario</p>
   ```

3. **Links Principais**
   ```html
   <li><a href="https://github.com/seu-usuario" target="_blank">GitHub</a></li>
   <li><a href="https://linkedin.com/in/seu-usuario" target="_blank">LinkedIn</a></li>
   ```

### Personalizando Cores

No arquivo `style.css`, modifique as CSS Variables:

```css
:root {
  --text-color: white;
  --bg-url: url(./assets/bg-mobile.jpg);
  --stroke-color: rgba(255, 255, 255, 0.5);
  --surface-color: rgba(255, 255, 255, 0.05);
  --surface-color-hover: rgba(0, 0, 0, 0.02);
  --highlight-color: rgba(255, 255, 255, 0.2);
}
```

### Adicionando Novos Links

1. Adicione um novo item na lista:
   ```html
   <li><a href="https://seu-link.com" target="_blank">Novo Link</a></li>
   ```

2. Adicione ícones sociais:
   ```html
   <a href="https://sua-rede-social.com" target="_blank">
     <ion-icon name="logo-nome-da-rede"></ion-icon>
   </a>
   ```

---

## 🔖 Layout

### Características do Design
- **Mobile First**: Desenvolvido priorizando dispositivos móveis
- **Tema Duplo**: Versões clara e escura
- **Glassmorphism**: Efeitos de vidro fosco nos elementos
- **Micro-interações**: Animações sutis para melhor UX

---

## 📱 Responsividade

O projeto é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Mobile**: 320px - 699px
- **Desktop**: 700px+
- **Breakpoint principal**: 700px (definido no CSS)

### Media Queries Implementadas
```css
@media (min-width: 700px) {
  :root {
    --bg-url: url(./assets/bg-desktop.jpg);
  }
  .light {
    --bg-url: url(./assets/bg-desktop-light.jpg);
  }
}
```

---

## 🌟 Funcionalidades Técnicas

### Alternância de Tema
- Utiliza `classList.toggle()` para alternar classes CSS
- CSS Variables para mudança dinâmica de propriedades
- Animações keyframe para transição suave do switch

### Efeitos Visuais
- **Backdrop Filter**: Efeito de desfoque nos elementos
- **Transitions**: Transições suaves em hover
- **Box Shadow**: Sombras para profundidade
- **Border Radius**: Cantos arredondados modernos

### Performance
- **Otimização de imagens**: Formatos adequados para web
- **CSS minificado**: Estilos organizados e otimizados
- **JavaScript leve**: Código mínimo e eficiente

---


## 📝 Licença

Este projeto está sob a licença MIT.


