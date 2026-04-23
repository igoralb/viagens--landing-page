# 🌍 TravelHub - Landing Page de Viagens

Uma landing page moderna, responsiva e acessível dedicada a viagens por vilarejos europeus. Este projeto foi desenvolvido com as melhores práticas de HTML semântico, CSS avançado e acessibilidade web, implementando navegação interna suave, menu responsivo e design mobile-first.

## 🎯 Sobre o Projeto

**TravelHub** é uma landing page profissional de viagens que apresenta:
- Um banner atrativo com imagem de paisagem europeia
- Navegação fluida entre múltiplas seções
- Menu sanduíche (hamburger) para dispositivos móveis
- Design responsivo para todos os tamanhos de tela
- Acessibilidade completa (WCAG)

## ✅ Conformidade com Requisitos

### Requisitos Principais
- ✅ Banner dentro da tag `<main>`
- ✅ Navegação `<nav>` com links internos
- ✅ Botão "Voltar ao Topo" funcional

### Especificações de Design
- ✅ Banner com imagem de vilarejo europeu
- ✅ Texto overlay (h2) acima do banner
- ✅ Navegação interna com IDs
- ✅ Sem abertura em novas abas
- ✅ Hover effects em todos os elementos interativos
- ✅ Transitions suaves de CSS

### Semântica HTML5
- ✅ Tags semânticas: `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- ✅ Uso correto de classes e IDs
- ✅ Atributos aria-label para acessibilidade

## 📋 Características

✅ **Design Responsivo** - Adaptado para móvel, tablet e desktop com menu sanduíche  
✅ **Menu Hamburger** - Navegação colapsível para telas pequenas (até 768px)  
✅ **Navegação Suave** - Scroll behavior smooth com transições CSS  
✅ **Navegação Interna** - Links com âncoras (#ID) sem recarregar página  
✅ **Banner Atrativo** - Seção hero com imagem real e overlay de texto  

### 🧳 3 Seções Principais:
1. **Minha Viagem** - 6 cards com tipos de experiências
2. **Conselhos** - 8 dicas essenciais para viajantes
3. **Nos Encontre** - Contato, redes sociais, newsletter e botão "Voltar ao Topo"

✅ **Hover Effects** - Todos elementos interativos mudam de aparência  
✅ **Semântica HTML5** - Tags `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`  
✅ **Acessibilidade** - ARIA labels, navegação por teclado, respeito a preferências de movimento  
✅ **Animações Suaves** - Transições CSS elegantes e keyframes  
✅ **Sem JavaScript** - Funcionalidade completa apenas com HTML e CSS

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Layout com Grid e Flexbox, animações, menu hamburger
- **Sem JavaScript** - Funcionalidade completa com HTML e CSS puro

## 📁 Estrutura do Projeto

```
devstart/
├── index.html                          # Arquivo HTML principal (250+ linhas)
├── style.css                           # Folha de estilo (600+ linhas)
├── beautiful-landscape-mother-nature.jpg # Imagem do banner
└── README.md                           # Este arquivo
```

### Organização das Seções

1. **Banner (Home)** - Hero section com CTA
2. **Minha Viagem** - 6 cards de experiências
3. **Conselhos** - 8 dicas de viagem
4. **Nos Encontre** - Contato, newsletter e botão "Voltar ao Topo"
5. **Footer** - Rodapé com créditos

## 🚀 Como Executar

### Opção 1: Live Server (Recomendado)

1. Abra o VS Code
2. Clique com botão direito no arquivo `index.html`
3. Selecione **"Open with Live Server"**
4. A página abrirá automaticamente no seu navegador padrão

### Opção 2: Abrir Diretamente

1. Simplesmente abra o arquivo `index.html` no navegador

### Opção 3: Usar um Editor Online

- [CodePen](https://codepen.io/) - Cole o código HTML e CSS
- [JSFiddle](https://jsfiddle.net/) - Alternativa ao CodePen

## 📱 Responsividade

O projeto foi desenvolvido com "Mobile First" e possui breakpoints para:

- **Desktop (769px+)** - Navegação horizontal completa
- **Tablet (até 768px)** - Menu hamburger, grid ajustado para 2 colunas
- **Mobile (até 480px)** - Interface otimizada, menu hamburger ativo

### Menu Hamburger (Mobile)
- Aparece automaticamente em telas ≤ 768px
- 3 linhas animadas que viram um "X" ao abrir
- Menu dropdown com background gradiente
- Funciona sem JavaScript (checkbox CSS trick)

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Primária | `#1e3c72` | Headers, títulos principais |
| Secundária | `#2a5298` | Botões, links |
| Destaque | `#ff6b6b` | Botões de ação, hover effects |
| Fundo Claro | `#f8f9fa` | Backgrounds alternativos |
| Texto Escuro | `#2c3e50` | Corpo de texto |

## 🔍 Funcionalidades de Navegação

- **Navegação Sticky** - Barra de navegação fixa no topo durante scroll
- **Scroll Suave** - Navegação entre seções com efeito suave (smooth scroll)
- **Links Internos** - Use `#home`, `#trip-me`, `#meet-us`, `#advice` para navegar
- **Volta ao Topo** - Botões em cada seção para voltar à navegação principal

## ♿ Acessibilidade

- ✅ Estrutura semântica apropriada (HTML5)
- ✅ ARIA labels em elementos interativos
- ✅ Contraste de cores adequado (WCAG AA)
- ✅ Navegação por teclado funcional
- ✅ Respeito às preferências `prefers-reduced-motion`
- ✅ Labels descritivos em formulários
- ✅ Links com `aria-label` onde necessário

## 📄 Requisitos Implementados

Conforme solicitado no briefing do projeto, **TODOS os requisitos foram atendidos**:

### Requisitos Principais ✅
1. ✅ Banner com imagem dentro da `<main>`
2. ✅ Navegação `<nav>` mínima e funcional
3. ✅ Navegação direcionada ao topo (#topo)

### Especificações ✅
1. ✅ Banner com imagem real de vilarejo europeu
2. ✅ Texto overlay (h2) no banner
3. ✅ `<section>` com background-image
4. ✅ Navegações internas com href="#id"
5. ✅ Sem `target="_blank"` (mesma aba)
6. ✅ `:hover` em todos elementos interativos
7. ✅ Transitions suaves de background

### Boas Práticas ✅
1. ✅ Tags semânticas: `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
2. ✅ IDs para navegação interna
3. ✅ Classes para elementos repetidos (`.card`, `.contact-card`, `.advice-card`)
4. ✅ Acessibilidade com ARIA labels
5. ✅ Layout responsivo (Mobile First)
6. ✅ Menu hamburger para telas pequenas

## 💡 Melhorias Futuras Possíveis

- Adicionar validação de formulário com JavaScript
- Integrar com API de back-end para newsletter
- Implementar carrossel de imagens com lightbox
- Adicionar modal para mais informações detalhadas
- Integrar Google Maps para localização
- Suporte a múltiplos idiomas
- Dark mode toggle
- Animações ao scroll (Intersection Observer)

## 👨‍💻 Autor

Desenvolvido como prática educacional de desenvolvimento web.

## 📝 Licença

Este projeto é livre para uso educacional e comercial.

---

## 🚀 Deployment

Para colocar este projeto online:

1. **GitHub Pages** - Hospedagem gratuita diretamente do repositório
2. **Vercel** - Deploy automático com cada push
3. **Netlify** - Hospedagem gratuita com CI/CD
4. **Firebase Hosting** - Google cloud hosting
5. **Surge.sh** - Deploy rápido e fácil

### Passos para GitHub Pages:
```bash
1. Push o código para GitHub
2. Vá em Settings > Pages
3. Selecione "main branch" como source
4. Seu site estará em: https://seu-usuario.github.io/viagens--landing-page
```

---

**Status do Projeto:** ✅ Completo e Pronto para Deploy

Desenvolvido em abril de 2026 como projeto educacional de landing page responsiva.

