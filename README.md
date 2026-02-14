# 📱 Portfólio Sophia Sacramento

Landing Page profissional desenvolvida como portfólio para apresentação de carreira, projetos e habilidades na área de QA/Tester.

## 📌 Sobre o Projeto

Este projeto consiste em uma Landing Page responsiva e moderna, desenvolvida para apresentar a trajetória profissional de Sophia Sacramento, especialista em Quality Assurance. O site conta com seções organizadas para facilitar a navegação e apresentação de informações relevantes sobre experiência, projetos e metodologias de trabalho.

## 👥 Equipe

João Marinho
Ana Cleide
Rayane Mayara
Emilly Matias
Felipe Machado

## 🎯 Objetivo

Criar uma presença online profissional que destaque:
- Experiência em testes automatizados e manuais
- Portfólio de projetos desenvolvidos
- Conhecimento em metodologias ágeis
- Facilitar contato profissional

## ✨ Funcionalidades

- **Navegação Responsiva**: Menu adaptável para dispositivos móveis com animações suaves
- **Seção Home**: Apresentação inicial com foto de perfil e descrição profissional
- **Sobre Mim**: Informações detalhadas sobre experiência e formação
- **Hard Skills**: Destaque de competências técnicas com ícones das tecnologias
- **Projetos**: Cards interativos com links diretos para repositórios no GitHub
- **Metodologias**: Lista de frameworks e metodologias utilizadas
- **Rodapé com Contatos**: Links para e-mail e GitHub

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica do conteúdo
- **CSS3**: Estilização com técnicas modernas
  - Flexbox e Grid Layout
  - Animações e transições
  - Media queries para responsividade
- **JavaScript**: Interatividade do menu mobile
- **Google Fonts**: Tipografia (Poppins e Oleo Script)

## 🎨 Paleta de Cores

- `#E7A49B` - Rosa claro (fundo seções)
- `#FFBBB2` - Rosa pastel (gradientes)
- `#B67770` - Terracota (gradientes)
- `#453C3C` - Marrom escuro (texto e botões)
- `#2B2B2B` - Cinza escuro (hover effects)
- `#FFFFFF` - Branco (textos e elementos)

## 📂 Estrutura do Projeto

```
/
├── index.html
├── README.md
├── Assets/
│   ├── css/
│   │   └── style.css
│   ├── img/
│   │   ├── background.jpg
│   │   ├── sophiaSacramento.jpg
│   │   ├── Cypress.png
│   │   ├── js.png
│   │   ├── selenium.png
│   │   ├── git.png
│   │   ├── github.png
│   │   ├── iconVerificado.png
│   │   └── [imagens de projetos]
│   ├── js/
│   │   └── main.js
│   ├── menuMobileIcon.svg
│   ├── email.svg
│   ├── github.svg
│   └── curriculoSophiaSacramento.pdf
```

## 🚀 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/sophiasacramento2/portfolio.git
```

2. Navegue até o diretório do projeto:
```bash
cd portfolio
```

3. Abra o arquivo `index.html` em seu navegador ou utilize uma extensão como Live Server no VS Code.

## 🎯 Destaques Técnicos

### Menu Mobile Interativo
Implementação de menu hambúrguer com animações escalonadas usando a função `onShow`:

```javascript
function onShow(){
    const menuMobile = document.querySelector('.navMobile');
    menuMobile.classList.toggle('open');
}
```

### Efeito Glassmorphism
Cards de projetos e hard skills utilizam backdrop-filter para criar efeito de vidro fosco moderno.

### Smooth Scroll
Navegação suave entre seções implementada via CSS:

```css
html {
    scroll-behavior: smooth;
}
```

## 🌐 Deploy

- **Plataforma sugerida**: Vercel 
- **Link do deploy**: (https://portifolioss.vercel.app)

## 📧 Contato

- **Email**: sophia.santos@arapiraca.ufal.br
- **GitHub**: [@sophiasacramento2](https://github.com/sophiasacramento2)

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo como base para seu próprio portfólio.

---

**Desenvolvido com 💜 por joão Marinho, Felipe Machado, Ana Cleide, Emilly Matias e Rayane Mayara**
