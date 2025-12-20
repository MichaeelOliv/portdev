🎨 Projeto 01 - Portifolio DEV

 📖 Sobre o Projeto

  O projeto é sobre o portifólio desenvolvido com tecnologias em css e html, com links para os principais trabalhos. Utilizando uma linguagem clara e intuititiva. O projeto consiste em uma interface de menu responsivo com navegação desktop e mobile.

![alt text](<assests/Sem título.jpg>)

✨ Conceitos Abordados 
🔹 CSS Nesting Aninhamento de seletores utilizando & (ampersand) Organização hierárquica de estilos Melhoria na legibilidade e manutenibilidade do código CSS CSS nativo moderno sem necessidade de pré-processadores 
🔹 Design Tokens (CSS Variables) Sistema de design com variáveis CSS customizadas Tokens de cores (primary, text, surface, border) Tokens de espaçamento (xs, sm, md, lg) Tokens de tipografia (font, text-sm, text-xs) Tokens de bordas e sombras (radius, shadow, blur) Suporte a tema escuro com prefers-color-scheme 
🔹 CSS Reset Reset completo de estilos padrão do navegador Box-sizing universal Normalização de elementos (a, button, ul, img) Smooth scrolling Font smoothing para melhor renderização de texto 
🔹 Responsive Design Layout desktop com header fixo Navegação mobile com bottom navigation Media queries para diferentes breakpoints Uso de env(safe-area-inset-bottom) para dispositivos iOS Container com largura máxima responsiva 
🔹 Acessibilidade Foco visível com :focus-visible Labels e aria-labels apropriados Suporte a prefers-reduced-motion para reduzir animações Estrutura HTML semântica 🔹 Glassmorphism Efeito de vidro com backdrop-filter: blur() Background semi-transparente Bordas sutis para profundidade 

📁 Estrutura do Projeto projeto-05-cssnesting/
 ├── css/ │ ├── base/ │ │ ├── _reset.css # Reset de estilos padrão │ │ └── _tokens.css # Design tokens (variáveis CSS) │ ├── components/ │ │ ├── _header.css # Estilos do header desktop │ │ └── _mobile-nav.css # Estilos da navegação mobile │ └── main.css # Arquivo principal (imports) ├── index.html # Estrutura HTML └── README.md # Documentação do projeto 🎯 Funcionalidades Desktop Header fixo com efeito glassmorphism Logo com ícone e texto Navegação horizontal com ícones Botões de ação (busca, notificações, perfil) Indicador de notificações não lidas Mobile Bottom navigation bar Ícones com labels Botão FAB (Floating Action Button) destacado Badge de notificações Layout otimizado para telas pequenas 🚀 Tecnologias Utilizadas HTML5 - Estrutura semântica CSS3 - Estilos modernos com Nesting nativo Lucide Icons - Biblioteca de ícones SVG CSS Custom Properties - Variáveis CSS para design system Media Queries - Design responsivo 🎨 Sistema de Cores Modo Claro Primary: #6366f1 (Índigo) Text: #1e293b (Slate escuro) Surface: rgba(255, 255, 255, 0.85) (Branco semi-transparente) Modo Escuro Text: #f1f5f9 (Slate claro) Surface: rgba(15, 23, 42, 0.9) (Slate escuro semi-transparente) Border: rgba(255, 255, 255, 0.1) (Borda clara) 📱 Responsividade Desktop: Header fixo no topo Mobile (< 768px): Bottom navigation fixo na parte inferior 🌐 Demo Acesse o projeto em: in100tiva.github.io/css-nesting

📚 Aprendizados Este projeto demonstra:

Como usar CSS Nesting nativo no navegador Organização de código CSS em módulos Criação de um design system com tokens Implementação de layouts responsivos modernos Boas práticas de acessibilidade Suporte a temas (claro/escuro) 👨‍💻 Autor Projeto In100tiva - Projeto educacional que visa democratizar e tornar acessível informações de Marketing, Design e Programação.

⭐ Se este projeto foi útil para você, considere dar uma estrela!