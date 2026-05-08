# 💍 O Senhor dos Anéis — Site Educativo

> Projeto web educativo inspirado na trilogia *O Senhor dos Anéis*, desenvolvido para praticar HTML5 e CSS3.

---

## 🧙‍♂️ Sobre o Projeto

Este site apresenta informações sobre o universo da Terra-média: história, personagens, sinopse, filmes, curiosidades e impacto cultural. A página de **Contato com a Terra-média** é um formulário temático como se você estivesse escrevendo ao Conselho de Elrond.

**Tecnologias utilizadas:**
- HTML5 semântico
- CSS3 (Flexbox, fontes do Google Fonts)
- Sem dependências externas ou frameworks

---

## 📁 Estrutura de Arquivos

```
Ola-mund0/
├── index.html                  → Página inicial (História e origem da Terra-média)
├── sinopse.html                → Sinopse da trilogia
├── imagem.html                 → Imagens e elenco
├── personagensprincipais.html  → Personagens principais
├── informacoes.html            → Informações técnicas dos filmes
├── ordemdosfilmes.html         → Tabela com a ordem dos filmes
├── Curiosidades.html           → Curiosidades sobre as filmagens
├── Impacto.html                → Impacto cultural da trilogia
├── contato.html                → Formulário de contato simples
├── carta.html                  → Formulário temático "Contato com a Terra-média"
├── README.md                   → Este arquivo
├── css/
│   └── style.css               → Toda a estilização do site
└── imagens_redme/
    ├── terra_media.png         → Mapa da Terra-média
    ├── senhor_dos_aneis.png    → Imagem do elenco
    ├── senhordosaneis_fundo.jpg→ Imagem de fundo (página de Impacto)
    └── icons8-orc-50.png       → Ícone da aba do navegador
```

---

## 🚀 Como Executar

1. **Baixe ou clone o repositório.**
2. **Abra o arquivo `index.html`** diretamente no seu navegador (Chrome, Firefox, Edge etc.).
3. **Navegue pelas páginas** usando o menu no topo de cada página.

### Usando o Live Server (VS Code) — Recomendado

Para ver as alterações em tempo real enquanto edita:

1. Instale a extensão **Live Server** no VS Code.
2. Clique com o botão direito no `index.html`.
3. Selecione **"Open with Live Server"**.

---

## 🧩 Funcionalidades

| Página | Conteúdo |
|---|---|
| `index.html` | História e etimologia da Terra-média |
| `sinopse.html` | Resumo da trilogia |
| `imagem.html` | Fotos do elenco |
| `personagensprincipais.html` | Lista dos personagens |
| `informacoes.html` | Ficha técnica dos filmes |
| `ordemdosfilmes.html` | Tabela com os 3 filmes |
| `Curiosidades.html` | Fatos curiosos das filmagens |
| `Impacto.html` | Impacto cultural (com fundo dinâmico) |
| `contato.html` | Formulário de contato simples |
| `carta.html` | Formulário temático completo |

### Campos do formulário (`carta.html`)
- Nome, e-mail e ano de nascimento
- Escolha de raça (radio buttons): Humano, Elfo, Anão, Hobbit
- Filme favorito e local preferido (select + optgroup)
- Habilidades (checkboxes)
- Nível de poder (input range)
- Reino de origem (datalist)
- Cor do manto (input color)
- Data da jornada e upload de relíquia
- Mensagem livre (textarea)
- Botões de enviar e limpar

---

## 🎨 Estilização (`css/style.css`)

O arquivo CSS está organizado em seções comentadas:

1. **Fontes** — Google Fonts (Cinzel para títulos, Lora para textos)
2. **Reset e Body** — Configurações base
3. **Container principal** — Largura e margens do `<main>`
4. **Cabeçalho e navegação** — Header e menu de links
5. **Títulos** — Estilo dourado temático
6. **Parágrafos e listas** — Espaçamento e legibilidade
7. **Layout** — Flexbox para duas colunas
8. **Imagens e figuras** — Moldura dourada
9. **Tabelas** — Estilo para a página de filmes
10. **Formulários** — Campos, labels, radio/checkbox e botões
11. **Página de Impacto** — Fundo com imagem

---

## 🛠️ Possíveis Melhorias Futuras

- [ ] Validação de formulário com JavaScript
- [ ] Tornar o site totalmente responsivo para celular
- [ ] Adicionar animações e transições mais elaboradas
- [ ] Conectar o formulário a um backend real

---

## 📌 Notas

- O projeto é **100% estático** — não precisa de servidor.
- O formulário com `action="#"` não envia dados para nenhum lugar (apenas para fins educativos).

---

## 📝 Licença

Distribuído sob licença **MIT**. Sinta-se livre para usar e modificar.
