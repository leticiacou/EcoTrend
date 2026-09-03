# EcoTrend

Interface front-end de um e-commerce fictício especializado em **produtos sustentáveis e ecológicos**, focado em promover um estilo de vida mais consciente.

O projeto é totalmente estático (sem back-end), desenvolvido como trabalho acadêmico para praticar **HTML5 semântico, CSS3 com CSS Grid Layout e Bootstrap**, com layout responsivo para desktop, tablet e mobile.

## Categorias de produtos

- Roupas e acessórios sustentáveis
- Produtos de beleza e cuidados pessoais naturais
- Itens para casa sustentáveis
- Tecnologia verde

## Páginas

| Arquivo | Descrição |
|---|---|
| `index.html` | Home: header com navegação e carrinho, carrossel de destaques e grid de produtos por categoria |
| `categorias.html` | Lista de produtos em grid com filtros laterais (preço, tipo de produto e marca) |
| `produto.html` | Detalhes do produto: imagem, nome, descrição completa, preço e botão "Adicionar ao Carrinho" |
| `contato.html` | Formulário de contato (nome, e-mail, assunto, mensagem) |

O footer (redes sociais, informações de contato e políticas da loja) está presente em todas as páginas.

## Tecnologias utilizadas

- **HTML5** semântico
- **CSS3** com **CSS Grid Layout** (`css/style.css`)
- **Bootstrap 5.3** — cards, carrossel, formulários, navbar e sistema de colunas (via CDN)
- **Font Awesome 6** — ícones (via CDN)
- **Google Fonts** — Poppins e Nunito (via CDN)

Nenhum framework JavaScript ou back-end é utilizado. O único script carregado é o `bootstrap.bundle.min.js`, necessário para o funcionamento do carrossel e do menu responsivo.

## Estrutura de arquivos

```
EcoTrend/
├── index.html
├── categorias.html
├── produto.html
├── contato.html
├── css/
│   └── style.css
├── assets/
│   └── img/          # imagens placeholder (SVG)
└── README.md
```

## Como rodar / visualizar

Por ser um site estático, basta abrir o arquivo `index.html` em qualquer navegador.

Alternativamente, para servir localmente:

```bash
# Python 3
python3 -m http.server 8080
# depois acesse http://localhost:8080
```

### Publicação

O projeto está pronto para hospedagem estática (GitHub Pages, Vercel, Netlify etc.). No GitHub Pages, basta habilitar a publicação a partir da branch principal, na pasta raiz (`/`).
