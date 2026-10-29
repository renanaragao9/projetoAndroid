# História do Mascote do Android

Página web estática que conta a curiosa história de como surgiu o mascote do Android, o **Bugdroid**. O projeto faz parte de uma série de "Curiosidades de Tecnologia" e foi desenvolvido como exercício de **HTML5 semântico** e **CSS3**.

## 📖 Sobre

O artigo apresenta:

- A primeira versão do mascote, os **Dandroids**, criada por Dan Morrill em 2007.
- O surgimento do **Bugdroid**, desenhado pela ilustradora russa Irina Blok.
- A inspiração por trás dos traços do mascote.
- Um vídeo complementar incorporado do YouTube.
- Um box lateral com a lista das versões do Android nomeadas em homenagem a doces (Cupcake a Pie).

## 🛠️ Tecnologias

- **HTML5** com marcação semântica (`header`, `nav`, `main`, `article`, `aside`, `picture`)
- **CSS3** com:
  - Variáveis CSS (`:root`) e paleta de cores do Android
  - Fontes customizadas (`@font-face` + Google Fonts "Bebas Neue")
  - Imagens responsivas via `<picture>` e `srcset`
  - Vídeo responsivo do YouTube
- **GitHub Pages** (Jekyll, tema `minimal`) para hospedagem

## 📁 Estrutura do projeto

```
projetoAndroid/
├── index.html          # Página principal com o artigo
├── proAndroid.css      # Folha de estilos
├── _config.yml         # Configuração do GitHub Pages / Jekyll
├── fontes/
│   └── idroid.otf      # Fonte customizada "Android"
├── imagens/            # Imagens do artigo e favicon
│   ├── dan-droids.png
│   ├── dan-droids-pq.png
│   ├── irina-blok.jpg
│   ├── irina-blok-pq.jpg
│   ├── bugdroid.png
│   └── favicon.ico
├── LICENSE
└── README.md
```

## 🚀 Como executar

Por ser um site estático, basta abrir o arquivo `index.html` no navegador:

```bash
# Clone o repositório
git clone <url-do-repositorio>
cd projetoAndroid

# Abra o index.html no navegador de sua preferência
```

Ou, opcionalmente, sirva localmente com um servidor simples:

```bash
# Com Python 3
python3 -m http.server 8000
# Acesse http://localhost:8000
```

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Desenvolvido como projeto de estudo de front-end. © 2022 renanaragao9
