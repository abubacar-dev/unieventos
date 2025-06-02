# UniEventos

Sistema de Gerenciamento de Eventos Acadêmicos da Universidade Lúrio

![UniEventos Banner](https://images.pexels.com/photos/2774556/pexels-photo-2774556.jpeg)

## 🎯 Sobre o Projeto

UniEventos é uma plataforma web estática desenvolvida para centralizar a divulgação e gestão de eventos acadêmicos da Universidade Lúrio. O sistema oferece uma interface moderna e responsiva, alinhada com a identidade visual institucional.

### 🌟 Características Principais

- 📅 Calendário acadêmico interativo
- 📱 Design responsivo para todos os dispositivos
- 🎨 Interface moderna e intuitiva
- ♿ Acessibilidade WCAG 2.1
- 🚀 Performance otimizada

## 🛠️ Tecnologias Utilizadas

- HTML5 Semântico
- CSS3 (Grid/Flexbox)
- Design System Personalizado
- Font Awesome para ícones
- Google Fonts (Roboto)

## 📂 Estrutura do Projeto

```
unieventos/
├── index.html                 # Página inicial
├── eventos/                   # Páginas de eventos
│   ├── lista-eventos.html
│   ├── detalhes-evento.html
│   └── inscricao.html
├── calendario/
│   └── calendario.html
├── admin/
│   ├── dashboard.html
│   ├── criar-evento.html
│   └── gerenciar-eventos.html
├── css/
│   ├── style.css             # Estilos principais
│   ├── responsive.css        # Media queries
│   └── admin.css             # Estilos administrativos
└── assets/
    ├── images/
    │   └── logos/
    └── fonts/
```

## 🚀 Começando

### Pré-requisitos

- Navegador web moderno
- Editor de código (VS Code recomendado)
- Conhecimento básico de HTML/CSS

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/unilurio/unieventos.git
```

2. Navegue até o diretório:
```bash
cd unieventos
```

3. Abra o `index.html` em seu navegador ou use um servidor local.

## 📱 Responsividade

O projeto é totalmente responsivo, com breakpoints em:

- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

## 🎨 Design System

### Cores

```css
:root {
  --primary-blue: #1E40AF;
  --secondary-blue: #93C5FD;
  --accent-blue: #3B82F6;
  /* Outras variáveis de cor */
}
```

### Tipografia

- Família: Roboto
- Pesos: 300, 400, 500, 700
- Tamanhos: 0.875rem - 2.5rem

## 📊 Componentes Principais

### Cards de Eventos

```html
<article class="event-card">
  <div class="event-card__image">
    <span class="event-card__badge">Conferência</span>
    <img src="event.jpg" alt="Evento">
  </div>
  <div class="event-card__content">
    <!-- Conteúdo do card -->
  </div>
</article>
```

### Formulários

```html
<form class="form">
  <div class="form__group">
    <label class="form__label">Campo</label>
    <input type="text" class="form__input">
  </div>
</form>
```

## 🔍 SEO e Acessibilidade

- Tags semânticas HTML5
- ARIA labels
- Alt text em imagens
- Estrutura de headings lógica
- Meta tags otimizadas

## ⚡ Performance

### Otimizações

- Imagens otimizadas
- CSS minificado
- Lazy loading
- Fontes otimizadas

### Métricas

- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1

## 🧪 Testes

### Compatibilidade

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers

### Validações

- HTML W3C
- CSS W3C
- Lighthouse scores
- Acessibilidade WCAG 2.1

## 📖 Documentação

- [Relatório Técnico](docs/technical-report.md)
- [Guia de Estilo](docs/style-guide.md)
- [Manual do Usuário](docs/user-manual.md)

## 🤝 Contribuindo

1. Fork o projeto
2. Crie sua branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✨ Agradecimentos

- Universidade Lúrio
- Equipe de desenvolvimento
- Contribuidores
- Comunidade acadêmica

## 📞 Contato

- Email: info@unilurio.ac.mz
- Website: www.unilurio.ac.mz
- Telefone: +258 26 218 250

## 🔄 Status do Projeto

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-green)
![Versão](https://img.shields.io/badge/versão-1.0.0-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)

---

Desenvolvido com ❤️ por Mussinady Abubacar