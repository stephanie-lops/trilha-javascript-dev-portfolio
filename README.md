# Portfólio Stephanie Lopes

Um portfólio interativo em HTML, CSS e JavaScript que apresenta minhas informações pessoais, habilidades, idiomas, experiência profissional e projetos. O conteúdo é carregado dinamicamente a partir de arquivos JSON.

## Funcionalidades

- Exibição de informações pessoais (nome, profissão, localização, contato)
- Seção Skills com hard skills e soft skills
- Seção Idiomas
- Seção Portfólio com projetos e links
- Seção Experiência Profissional
- Acordeon interativo para expandir e recolher seções
- Responsivo e compatível com dispositivos móveis

## Tecnologias utilizadas

- HTML5
- CSS3 (com múltiplos arquivos para modularidade)
- JavaScript (DOM e manipulação de dados via API local)
- Normalize.css para consistência de estilos entre navegadores
- Google Fonts (Open Sans)

## Estrutura do Projeto
``` bash
trilha-javascript-dev-portfolio/
├─ assets/
│  ├─ css/           # Arquivos de estilo
│  ├─ js/            # Scripts de interação e API
│  └─ img/           # Imagens do portfolio e ícones
├─ data/
│  └─ profile.json   # Informações dinâmicas do portfólio
└─ index.html
```

## Como usar

1. Clone o repositório:
```bash
git clone https://github.com/stephanie-lops/trilha-javascript-dev-portfolio.git
```
2. Abra index.html no seu navegador ou use um servidor local para carregar corretamente os dados do JSON.

3. Navegue pelas seções e veja o conteúdo carregado dinamicamente.

## JSON de perfil (data/profile.json)

O portfólio usa um arquivo JSON para carregar dinamicamente:
