
# 🌌 Star Wars Data Viewer

Este projeto é uma aplicação simples em HTML, CSS e JavaScript que consome a [Star Wars API (SWAPI)](https://swapi.dev/) para exibir informações sobre personagens e filmes do universo Star Wars. 

## 🖼️ Visão Geral

A aplicação permite carregar dinamicamente:
- Informações de personagens (nome, altura, peso, cores de cabelo e pele).  
- Detalhes dos filmes (título, diretor, produtor, data de lançamento e o icônico "opening crawl").  

Tudo é apresentado com um design temático inspirado no universo Star Wars.

![App Screenshot](assets/screenshots/demo.png)  
*(Insira uma captura de tela do projeto aqui)*

---

## 🚀 Funcionalidades

- **Página de Personagens:**
  - Lista personagens da franquia Star Wars.
  - Informações detalhadas: altura, massa, cor de cabelo e pele.
  - Dados carregados dinamicamente a partir da API SWAPI.

- **Página de Filmes:**
  - Lista filmes de Star Wars com detalhes como:
    - Título
    - Diretor
    - Produtor
    - Data de lançamento
    - Introdução ("Opening Crawl").
  - Layout responsivo para diferentes tamanhos de tela.

- **Navegação Simples:** Alternância entre páginas de personagens e filmes.

---

## 📂 Estrutura do Projeto

```plaintext
.
├── assets/
│   ├── css/
│   │   └── styles.css        # Estilos globais
│   ├── favicons/
│   │   └── favicon-16x16.png # Ícones do site
│   ├── js/
│   │   └── films.js          # Script da página de filmes
├── characters.html           # Página de personagens
├── films.html                # Página de filmes
├── index.html                # Página inicial
├── README.md                 # Este arquivo
└── LICENSE                   # Licença do projeto
```

---

## 🔧 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica das páginas.
- **CSS3:** Estilização responsiva e tema personalizado.
- **JavaScript:** Manipulação do DOM e consumo da API.
- **SWAPI:** API pública para dados de Star Wars.

---

## 🌈 Paleta de Cores

A aplicação utiliza uma paleta de cores temática para capturar o espírito de Star Wars:

| Cor              | Hex       | Descrição                |
|-------------------|-----------|--------------------------|
| **Amarelo Dourado** | `#FFD700` | Inspirado no texto de abertura. |
| **Preto Profundo** | `#121212` | Fundo temático do espaço.      |
| **Cinza Espaço**   | `#333333` | Estilo das naves e uniformes. |
| **Bege Rebelde**   | `#F5DEB3` | Tons neutros dos Rebeldes.    |

---

## ⚙️ Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/star-wars-data-viewer.git
   ```

2. Navegue até a pasta do projeto:
   ```bash
   cd star-wars-data-viewer
   ```

3. Abra o arquivo `index.html` em um navegador:
   - Para testar localmente, clique duas vezes no arquivo.
   - Ou use uma extensão como "Live Server" no VS Code.

---

## 📚 Aprendizados

Este projeto aborda os seguintes conceitos:
- Manipulação do DOM em JavaScript.
- Consumo de APIs REST com `fetch`.
- Organização e estruturação de arquivos em projetos front-end.
- Design responsivo com CSS.

---

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE). Você pode usá-lo, modificá-lo e distribuí-lo livremente.

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Se você encontrou problemas ou deseja adicionar novos recursos:

1. Faça um fork do repositório.
2. Crie um branch para sua feature ou correção:
   ```bash
   git checkout -b minha-nova-feature
   ```
3. Envie um pull request.

---

## 🛠️ Recursos Futuros

- **Barra de Pesquisa:** Permitir busca por personagens e filmes específicos.
- **Filtros Avançados:** Adicionar opções de filtro por atributos (como altura ou diretor).
- **Melhorias no Design:** Incorporar animações e um tema mais imersivo.

---

## 👾 Autor

**Seu Nome**  
🌐 [Portfólio](https://seuportfolio.com)  
🐦 [Twitter](https://twitter.com/seuperfil)  
📧 Email: voce@email.com

May the Force be with you! ✨
