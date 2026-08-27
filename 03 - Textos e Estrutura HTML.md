# ✍️ Textos e Estrutura HTML

---

## 🎯 Objetivo

Neste tutorial, vamos aprender como formatar textos e organizar o conteúdo de uma página HTML.

Também vamos conhecer elementos utilizados para destacar informações, criar quebras de linha, inserir separadores, comentários e organizar conteúdos em listas e seções.

---

## 🗺️ Conteúdo

| # | Conteúdo | Elementos principais |
|---|---|---|
| 1️⃣ | Formatação de texto | `<b>`, `<strong>`, `<i>`, `<em>` |
| 2️⃣ | Destaques | `<mark>`, `<small>` |
| 3️⃣ | Alterações no texto | `<del>`, `<ins>` |
| 4️⃣ | Subscrito e sobrescrito | `<sub>`, `<sup>` |
| 5️⃣ | Quebras e separadores | `<br>`, `<hr>` |
| 6️⃣ | Comentários | `<!-- -->` |
| 7️⃣ | Listas | `<ul>`, `<ol>`, `<li>` |
| 8️⃣ | Citações | `<blockquote>`, `<q>` |
| 9️⃣ | Estrutura semântica | `<header>`, `<nav>`, `<main>` |
| 🔟 | Exemplo completo | Página HTML |
| 1️⃣1️⃣ | Exercício | Prática |

---

# 1️⃣ Formatação de texto

HTML possui elementos que permitem indicar diferentes significados e níveis de destaque para partes de um texto.

### 📊 Principais elementos

| Elemento | Função |
|---|---|
| `<b>` | Destaca o texto em negrito |
| `<strong>` | Indica texto de grande importância |
| `<i>` | Apresenta texto em itálico |
| `<em>` | Dá ênfase ao texto |

### 💻 Exemplos

```html
<p>
    Este é um texto <b>em negrito</b>.
</p>

<p>
    Este é um texto <strong>importante</strong>.
</p>

<p>
    Este é um texto <i>em itálico</i>.
</p>

<p>
    Este texto possui <em>ênfase</em>.
</p>
```

---

# 2️⃣ Destaques de texto 🔎

Alguns elementos podem ser utilizados para destacar ou modificar a apresentação de determinadas partes do conteúdo.

### 🟡 `<mark>`

Utilizado para destacar um trecho.

```html
<p>
    Este é um texto com uma
    <mark>informação importante</mark>.
</p>
```

### 🔽 `<small>`

Utilizado para apresentar um texto menor.

```html
<p>
    Texto principal
    <small>Informação complementar</small>
</p>
```

### 📊 Comparação

| Elemento | Utilização |
|---|---|
| `<mark>` 🟡 | Destacar um trecho |
| `<small>` 🔽 | Representar texto menor |

---

# 3️⃣ Alterações no texto ✏️

Também podemos representar informações que foram removidas ou adicionadas.

### ❌ `<del>`

Representa um texto que foi removido.

```html
<p>
    Preço anterior:
    <del>R$ 100,00</del>
</p>
```

### ✅ `<ins>`

Representa um texto que foi inserido.

```html
<p>
    Novo preço:
    <ins>R$ 80,00</ins>
</p>
```

### 💻 Exemplo

```html
<p>
    O valor era <del>R$ 100,00</del>
    e passou para <ins>R$ 80,00</ins>.
</p>
```

---

# 4️⃣ Subscrito e sobrescrito 🔢

Os elementos `<sub>` e `<sup>` permitem representar textos abaixo ou acima da linha normal.

### ⬇️ Subscrito

```html
<p>
    H<sub>2</sub>O
</p>
```

### ⬆️ Sobrescrito

```html
<p>
    X<sup>2</sup>
</p>
```

### 📊 Exemplos

| Elemento | Exemplo | Utilização |
|---|---|---|
| `<sub>` | H₂O | Fórmulas químicas |
| `<sup>` | X² | Potências e referências |

---

# 5️⃣ Quebras e separadores

## ↩️ `<br>`

A tag `<br>` cria uma quebra de linha.

```html
<p>
    Primeira linha<br>
    Segunda linha<br>
    Terceira linha
</p>
```

### 📌 Estrutura

```text
Primeira linha
      ↓
    <br>
      ↓
Segunda linha
      ↓
    <br>
      ↓
Terceira linha
```

---

## ➖ `<hr>`

A tag `<hr>` cria uma separação temática entre conteúdos.

```html
<h2>Primeira seção</h2>

<p>
    Conteúdo da primeira seção.
</p>

<hr>

<h2>Segunda seção</h2>

<p>
    Conteúdo da segunda seção.
</p>
```

### 📊 Comparação

| Elemento | Função |
|---|---|
| `<br>` ↩️ | Quebra de linha |
| `<hr>` ➖ | Separação entre conteúdos |

---

# 6️⃣ Comentários HTML 💬

Comentários são utilizados para inserir observações no código sem exibi-las na página.

### 🧩 Estrutura

```html
<!-- Este é um comentário -->
```

### 💻 Exemplo

```html
<h1>Minha página</h1>

<!-- Este comentário não será exibido no navegador -->

<p>
    Conteúdo da página.
</p>
```

### 📌 Utilizações

| Utilização | Exemplo |
|---|---|
| 📝 Explicar código | `<!-- Título principal -->` |
| 🗂️ Organizar código | `<!-- Seção de contato -->` |
| 🔧 Facilitar manutenção | `<!-- Formulário -->` |

> 💡 **Importante:** comentários aparecem no código-fonte, mas não são exibidos como conteúdo normal da página.

---

# 7️⃣ Listas HTML 📋

As listas permitem organizar informações em sequência ou em grupos.

Existem dois tipos básicos:

- 🔵 Lista não ordenada
- 🔢 Lista ordenada

---

## 🔵 Lista não ordenada

Utiliza `<ul>` e `<li>`.

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### 📊 Estrutura

| Elemento | Função |
|---|---|
| `<ul>` | Cria a lista não ordenada |
| `<li>` | Define um item da lista |

---

## 🔢 Lista ordenada

Utiliza `<ol>` e `<li>`.

```html
<ol>
    <li>Planejamento</li>
    <li>Desenvolvimento</li>
    <li>Testes</li>
</ol>
```

### 📊 Comparação

| Tipo | Elementos | Organização |
|---|---|---|
| 🔵 Não ordenada | `<ul>` + `<li>` | Itens sem sequência |
| 🔢 Ordenada | `<ol>` + `<li>` | Itens numerados |

---

## 🧩 Listas aninhadas

Uma lista pode conter outra lista.

```html
<ul>

    <li>
        Desenvolvimento Web

        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>

    </li>

    <li>
        Banco de Dados
    </li>

</ul>
```

---

# 8️⃣ Citações HTML 💬

HTML possui elementos específicos para representar citações.

## 📖 `<blockquote>`

Utilizado para citações maiores.

```html
<blockquote>
    O conhecimento é construído por meio da prática.
</blockquote>
```

## 💬 `<q>`

Utilizado para pequenas citações.

```html
<p>
    Ele disse:
    <q>Aprender HTML é o primeiro passo.</q>
</p>
```

### 📊 Comparação

| Elemento | Utilização |
|---|---|
| `<blockquote>` | Citação maior |
| `<q>` | Citação curta |

---

# 9️⃣ Estrutura semântica HTML 🧩

Elementos semânticos ajudam a organizar o significado e a estrutura do conteúdo da página.

### 📊 Principais elementos

| Elemento | Função |
|---|---|
| `<header>` | Cabeçalho |
| `<nav>` | Área de navegação |
| `<main>` | Conteúdo principal |
| `<section>` | Seção de conteúdo |
| `<article>` | Conteúdo independente |
| `<footer>` | Rodapé |

### 🧠 Estrutura

```text
<html>
 │
 └── <body>
      │
      ├── <header>
      │
      ├── <nav>
      │
      ├── <main>
      │    │
      │    ├── <section>
      │    │
      │    └── <article>
      │
      └── <footer>
```

---

# 🧪 1️⃣0️⃣ Exemplo completo

Agora vamos combinar os elementos apresentados em uma única página.

```html
<!DOCTYPE html>

<html lang="pt-BR">

<body>

    <header>

        <h1>Minha Página</h1>

        <p>
            <strong>Bem-vindo</strong> à minha página HTML.
        </p>

    </header>

    <nav>

        <a href="index.html">
            Início
        </a>

        <br>

        <a href="sobre.html">
            Sobre
        </a>

    </nav>

    <hr>

    <main>

        <section>

            <h2>Sobre o projeto</h2>

            <p>
                Este projeto utiliza
                <mark>HTML</mark>
                para estruturar seu conteúdo.
            </p>

            <p>
                Tecnologias utilizadas:
            </p>

            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>

        </section>

        <section>

            <h2>Exemplo</h2>

            <p>
                Fórmula da água:
                H<sub>2</sub>O
            </p>

            <p>
                Exemplo matemático:
                X<sup>2</sup>
            </p>

        </section>

        <article>

            <h2>Informação</h2>

            <blockquote>
                Este é um exemplo de citação
                dentro de um artigo.
            </blockquote>

        </article>

    </main>

    <footer>

        <hr>

        <p>
            <small>
                © 2026 - Minha Página
            </small>
        </p>

    </footer>

</body>

</html>
```

---

# 🔎 Analisando a estrutura

| Elemento | Papel |
|---|---|
| `<header>` 🏠 | Cabeçalho |
| `<nav>` 🧭 | Navegação |
| `<main>` 📄 | Conteúdo principal |
| `<section>` 📚 | Organização do conteúdo |
| `<article>` 📰 | Conteúdo independente |
| `<footer>` 📌 | Rodapé |
| `<ul>` 📋 | Lista |
| `<blockquote>` 💬 | Citação |

---

# 📚 Resumo

| Elemento | Função |
|---|---|
| `<b>` | Negrito |
| `<strong>` | Importância |
| `<i>` | Itálico |
| `<em>` | Ênfase |
| `<mark>` | Destaque |
| `<small>` | Texto menor |
| `<del>` | Texto removido |
| `<ins>` | Texto inserido |
| `<sub>` | Subscrito |
| `<sup>` | Sobrescrito |
| `<br>` | Quebra de linha |
| `<hr>` | Separação |
| `<!-- -->` | Comentário |
| `<ul>` | Lista não ordenada |
| `<ol>` | Lista ordenada |
| `<li>` | Item da lista |
| `<blockquote>` | Citação longa |
| `<q>` | Citação curta |
| `<header>` | Cabeçalho |
| `<nav>` | Navegação |
| `<main>` | Conteúdo principal |
| `<section>` | Seção |
| `<article>` | Artigo |
| `<footer>` | Rodapé |

---

# 🚀 Exercício

Crie uma página HTML utilizando os conceitos deste tutorial.

| Requisito | Elemento |
|---|---|
| 📄 Estrutura HTML5 | `<!DOCTYPE html>` |
| 🌎 Idioma | `lang="pt-BR"` |
| 🏠 Cabeçalho | `<header>` |
| 🧭 Navegação | `<nav>` |
| 📄 Conteúdo principal | `<main>` |
| 📚 Duas seções | `<section>` |
| 🏷️ Títulos | `<h1>` e `<h2>` |
| 📝 Parágrafos | `<p>` |
| 🟡 Texto destacado | `<mark>` |
| 🔵 Lista | `<ul>` |
| 🔢 Lista numerada | `<ol>` |
| 💬 Citação | `<blockquote>` |
| ➖ Separação | `<hr>` |
| 📌 Rodapé | `<footer>` |

### ✅ Checklist

- [ ] Criar a estrutura HTML5
- [ ] Definir `lang="pt-BR"`
- [ ] Criar um `<header>`
- [ ] Criar um `<nav>`
- [ ] Criar um `<main>`
- [ ] Criar pelo menos duas `<section>`
- [ ] Utilizar títulos e parágrafos
- [ ] Utilizar uma lista não ordenada
- [ ] Utilizar uma lista ordenada
- [ ] Utilizar `<mark>`
- [ ] Utilizar `<blockquote>`
- [ ] Utilizar `<br>` e `<hr>`
- [ ] Criar um `<footer>`
