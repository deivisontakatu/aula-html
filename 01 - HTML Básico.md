# 📘 HTML Básico

---

## 🎯 Objetivo

Neste tutorial, vamos aprender os principais elementos utilizados para criar a estrutura básica de uma página HTML.

Ao final, você será capaz de criar um documento HTML simples utilizando títulos, parágrafos e links.

---

## 🗺️ Conteúdo

| # | Conteúdo | Elementos principais |
|---|---|---|
| 1️⃣ | Documento HTML | `<!DOCTYPE>`, `<html>`, `<body>` |
| 2️⃣ | DOCTYPE | `<!DOCTYPE html>` |
| 3️⃣ | Títulos | `<h1>` até `<h6>` |
| 4️⃣ | Parágrafos | `<p>` |
| 5️⃣ | Links | `<a>` |
| 6️⃣ | Estrutura | Organização dos elementos |
| 7️⃣ | Exemplo completo | Página HTML |
| 8️⃣ | Exercício | Prática |

---

# 1️⃣ Documento HTML

Um documento HTML possui uma estrutura básica que define como o navegador deve interpretar a página.

Todo documento HTML5 deve começar com uma declaração de tipo de documento e possuir as tags `<html>` e `<body>`.

### 🧩 Estrutura básica

```text
<!DOCTYPE html>
      ↓
   <html>
      ↓
   <body>
      ↓
Conteúdo visível
      ↓
  </body>
   </html>
```

### 📊 Principais elementos

| Elemento | Função |
|---|---|
| `<!DOCTYPE html>` | Indica que o documento utiliza HTML5 |
| `<html>` | Define o início do documento HTML |
| `</html>` | Define o final do documento |
| `<body>` | Contém o conteúdo visível da página |
| `</body>` | Finaliza o conteúdo da página |

---

## 💻 Primeiro exemplo

```html
<!DOCTYPE html>
<html>

<body>

    <h1>My First Heading</h1>

    <p>My first paragraph.</p>

</body>

</html>
```

### 🔎 O que acontece?

O navegador interpreta o código e apresenta o conteúdo que está dentro do `<body>`.

---

# 2️⃣ A declaração `<!DOCTYPE>`

A declaração `<!DOCTYPE>` informa ao navegador qual tipo de documento está sendo utilizado.

No HTML5, utilizamos:

```html
<!DOCTYPE html>
```

### 📌 Características

| Característica | Descrição |
|---|---|
| 📍 Posição | Primeira linha do documento |
| 🔢 Quantidade | Utilizada uma única vez |
| 🌐 HTML5 | Utiliza `<!DOCTYPE html>` |
| 🔤 Formato | Não depende de letras maiúsculas ou minúsculas |

> 💡 **Dica:** sempre comece seus documentos HTML5 com `<!DOCTYPE html>`.

---

# 3️⃣ Títulos HTML

Os títulos são definidos pelas tags `<h1>` até `<h6>`.

O `<h1>` representa o título de maior importância e o `<h6>` representa o de menor importância.

### 📊 Hierarquia

| Tag | Utilização |
|---|---|
| `<h1>` | Título principal |
| `<h2>` | Título de segundo nível |
| `<h3>` | Título de terceiro nível |
| `<h4>` | Título de quarto nível |
| `<h5>` | Título de quinto nível |
| `<h6>` | Título de sexto nível |

### 💻 Exemplo

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

### 🧠 Hierarquia de conteúdo

```text
<h1>Minha Página
│
├── <h2>Sobre
│
├── <h2>Projetos
│   ├── <h3>Projeto 1
│   └── <h3>Projeto 2
│
└── <h2>Contato
```

---

# 4️⃣ Parágrafos HTML

Os parágrafos são definidos utilizando a tag `<p>`.

Eles são utilizados para organizar textos e informações em blocos.

### 🧩 Estrutura

```html
<p>Texto do parágrafo.</p>
```

### 💻 Exemplo

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

### 📊 Estrutura

| Elemento | Função |
|---|---|
| `<p>` | Inicia um parágrafo |
| Texto | Conteúdo do parágrafo |
| `</p>` | Finaliza o parágrafo |

---

# 5️⃣ Links HTML 🔗

Os links são criados utilizando a tag `<a>`.

O atributo `href` indica o endereço para o qual o usuário será direcionado.

### 🧩 Estrutura

```html
<a href="endereco">
    Texto do link
</a>
```

### 💻 Exemplo

```html
<a href="https://www.google.com">
    Google
</a>
```

### 📊 Componentes

| Parte | Função |
|---|---|
| `<a>` | Cria o link |
| `href` | Define o endereço |
| URL | Define o destino |
| Texto | Conteúdo apresentado ao usuário |
| `</a>` | Finaliza o link |

---

## 🌐 Vários links

```html
<h2>Links úteis</h2>

<a href="https://www.google.com">
    Google
</a>

<br>

<a href="https://www.github.com">
    GitHub
</a>

<br>

<a href="https://www.youtube.com">
    YouTube
</a>
```

---

# 6️⃣ Estrutura de uma página

Podemos combinar os elementos aprendidos para criar uma estrutura simples.

```text
Documento HTML
│
├── DOCTYPE
│
├── HTML
│   │
│   └── BODY
│       │
│       ├── H1
│       ├── H2
│       ├── P
│       ├── P
│       └── A
```

### 📌 Exemplo

```html
<!DOCTYPE html>

<html>

<body>

    <h1>Minha Página</h1>

    <h2>Sobre mim</h2>

    <p>
        Meu nome é João e estou aprendendo HTML.
    </p>

    <h2>Meus projetos</h2>

    <p>
        Aqui estão alguns dos meus projetos.
    </p>

    <a href="https://www.github.com">
        Meu GitHub
    </a>

</body>

</html>
```

---

# 🧪 7️⃣ Exemplo completo

```html
<!DOCTYPE html>

<html>

<body>

    <h1>Minha Primeira Página HTML</h1>

    <h2>Sobre a página</h2>

    <p>
        Esta é minha primeira página desenvolvida utilizando HTML.
    </p>

    <p>
        Estou aprendendo os principais elementos da linguagem.
    </p>

    <h2>Links</h2>

    <a href="https://www.google.com">
        Google
    </a>

    <br>

    <a href="https://www.github.com">
        GitHub
    </a>

</body>

</html>
```

---

# 📚 8️⃣ Resumo

| Elemento | Função |
|---|---|
| `<!DOCTYPE html>` 📄 | Define HTML5 |
| `<html>` 🌐 | Define o documento HTML |
| `<body>` 👁️ | Contém o conteúdo visível |
| `<h1>` até `<h6>` 🏷️ | Criam títulos |
| `<p>` 📝 | Cria parágrafos |
| `<a>` 🔗 | Cria links |
| `href` 🌐 | Define o destino do link |

---

# 🚀 Exercício

Crie uma página HTML contendo:

| Requisito | Elemento |
|---|---|
| 📄 Documento HTML5 | `<!DOCTYPE html>` |
| 🌐 Estrutura HTML | `<html>` |
| 👁️ Conteúdo visível | `<body>` |
| 🏷️ Título principal | `<h1>` |
| 🏷️ Dois subtítulos | `<h2>` |
| 📝 Três parágrafos | `<p>` |
| 🔗 Dois links | `<a>` |

### ✅ Checklist

- [ ] Utilizar `<!DOCTYPE html>`
- [ ] Criar `<html>`
- [ ] Criar `<body>`
- [ ] Adicionar um `<h1>`
- [ ] Adicionar dois `<h2>`
- [ ] Criar três `<p>`
- [ ] Criar dois links com `<a>`
- [ ] Utilizar `href` nos links
