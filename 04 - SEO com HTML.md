# 🔎 SEO com HTML

---

## 🎯 Objetivo

Neste tutorial, vamos aprender os principais conceitos de **SEO (Search Engine Optimization)** e como aplicar boas práticas diretamente no HTML.

Também vamos aprender como estruturar uma página para facilitar sua compreensão por mecanismos de busca, melhorar a acessibilidade e proporcionar uma melhor experiência para os usuários.

Ao final, você será capaz de criar uma página HTML utilizando elementos e atributos que contribuem para uma estrutura mais adequada para SEO.

---

## 🗺️ Conteúdo

| # | Conteúdo | Principais elementos |
|---|---|---|
| 1️⃣ | O que é SEO | Conceitos básicos |
| 2️⃣ | Como os buscadores funcionam | Crawling e indexação |
| 3️⃣ | Estrutura do documento | `<html>`, `<head>`, `<body>` |
| 4️⃣ | Título da página | `<title>` |
| 5️⃣ | Meta description | `<meta>` |
| 6️⃣ | Idioma e responsividade | `lang`, `viewport` |
| 7️⃣ | Headings | `<h1>` até `<h6>` |
| 8️⃣ | HTML semântico | `<header>`, `<nav>`, `<main>` |
| 9️⃣ | Links e navegação | `<a>`, links internos |
| 🔟 | Imagens e acessibilidade | `alt`, `width`, `height` |
| 1️⃣1️⃣ | URL e canonical | `<link>` |
| 1️⃣2️⃣ | Indexação | `robots`, `noindex` |
| 1️⃣3️⃣ | Exemplo completo | Página otimizada |
| 1️⃣4️⃣ | Exercício | Prática |

---

# 1️⃣ O que é SEO? 🔎

SEO significa **Search Engine Optimization**, ou **Otimização para Mecanismos de Busca**.

É o conjunto de técnicas utilizadas para melhorar a estrutura, o conteúdo e a experiência de uma página, facilitando sua compreensão pelos mecanismos de busca.

Quando uma página possui uma estrutura adequada, ela pode ser melhor compreendida e apresentada nos resultados de pesquisa.

### 🎯 Principais objetivos

| Objetivo | Descrição |
|---|---|
| 🔎 Visibilidade | Facilitar a descoberta do conteúdo |
| 📄 Estrutura | Organizar melhor as informações |
| ♿ Acessibilidade | Facilitar o acesso ao conteúdo |
| 🧭 Navegação | Facilitar a navegação entre páginas |
| 📱 Experiência | Melhorar a utilização em diferentes dispositivos |

> 💡 **Importante:** SEO não significa simplesmente repetir palavras-chave. A qualidade, organização e relevância do conteúdo também são importantes.

---

# 2️⃣ Como os mecanismos de busca funcionam? 🌐

Os mecanismos de busca utilizam programas automatizados, conhecidos como **robôs**, para encontrar e analisar páginas disponíveis na Web.

Esse processo pode ser dividido, de forma simplificada, em duas etapas importantes:

```text
Página Web
    ↓
Crawling
    ↓
Conteúdo encontrado
    ↓
Indexação
    ↓
Página disponível para pesquisa
```

## 🔎 Crawling

O **crawling** é o processo utilizado pelos mecanismos de busca para descobrir páginas novas ou alterações realizadas em páginas existentes.

Os robôs podem encontrar páginas por meio de links e outras informações disponíveis na Web.

---

## 📚 Indexação

Depois de encontrar uma página, o mecanismo de busca pode analisar e armazenar suas informações em um índice.

Durante essa análise podem ser considerados elementos como:

- textos;
- títulos;
- headings;
- links;
- imagens;
- estrutura da página;
- conteúdo.

> 💡 Uma página existir na Web não significa necessariamente que ela aparecerá nos resultados de busca.

---

# 3️⃣ Estrutura do documento HTML 🧩

Uma página HTML possui diferentes partes e cada uma possui uma finalidade.

```text
<!DOCTYPE html>
      ↓
   <html>
      │
      ├── <head>
      │     ├── <title>
      │     └── <meta>
      │
      └── <body>
            └── Conteúdo
```

O `<head>` contém informações sobre o documento que não são apresentadas diretamente como conteúdo principal da página.

O `<body>` contém o conteúdo que será apresentado ao usuário.

### 💻 Exemplo

```html
<!DOCTYPE html>

<html lang="pt-BR">

<head>

    <title>Curso de HTML</title>

</head>

<body>

    <h1>Curso de HTML</h1>

    <p>
        Aprenda os fundamentos de HTML.
    </p>

</body>

</html>
```

---

# 4️⃣ Título da página `<title>` 🏷️

O elemento `<title>` define o título do documento HTML.

Ele é utilizado pelo navegador e pode ser apresentado nos resultados dos mecanismos de busca.

### ❌ Exemplo pouco descritivo

```html
<title>Site</title>
```

### ✅ Exemplo mais adequado

```html
<title>Curso de HTML | Desenvolvimento Web</title>
```

O título deve ser **claro, específico e relacionado ao conteúdo da página**.

> 💡 Evite utilizar títulos genéricos como `Site`, `Página`, `Home` ou `Documento`.

---

# 5️⃣ Meta description 📝

A `meta description` fornece uma breve descrição sobre o conteúdo da página.

```html
<meta
    name="description"
    content="Aprenda HTML e boas práticas para desenvolvimento web."
>
```

### 🎯 Características

Uma boa descrição deve:

- representar o conteúdo da página;
- ser clara;
- ser específica;
- despertar interesse no usuário;
- evitar excesso de palavras-chave.

### ❌ Evite

```html
<meta
    name="description"
    content="HTML HTML HTML curso HTML melhor HTML"
>
```

### ✅ Prefira

```html
<meta
    name="description"
    content="Aprenda HTML e desenvolva páginas web utilizando boas práticas."
>
```

---

# 6️⃣ Idioma e dispositivos móveis 📱

## 🌎 `lang`

O atributo `lang` informa o idioma principal do documento.

```html
<html lang="pt-BR">
```

Isso auxilia mecanismos de busca, navegadores e tecnologias assistivas na interpretação do conteúdo.

---

## 📱 `viewport`

A configuração de viewport permite que a página se adapte melhor a diferentes tamanhos de tela.

```html
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

> 💡 SEO também está relacionado à experiência do usuário. Uma página que funciona bem em computadores e dispositivos móveis proporciona uma experiência melhor.

---

# 7️⃣ Headings HTML 🏷️

Os headings organizam o conteúdo da página em diferentes níveis.

```text
<h1>
 │
 ├── <h2>
 │    ├── <h3>
 │    └── <h3>
 │
 └── <h2>
      └── <h3>
```

### 💻 Exemplo

```html
<h1>Desenvolvimento Web</h1>

<h2>HTML</h2>

<h3>Estrutura</h3>

<h3>Elementos</h3>

<h2>CSS</h2>

<h3>Seletores</h3>
```

### 📌 Boas práticas

- Utilize o `<h1>` para o assunto principal da página.
- Utilize `<h2>` para seções.
- Utilize `<h3>` para subseções.
- Mantenha uma hierarquia lógica.
- Não utilize headings apenas para aumentar o tamanho do texto.

> 💡 A aparência dos títulos deve ser controlada principalmente utilizando CSS.

---

# 8️⃣ HTML semântico 🧩

Os elementos semânticos ajudam a representar a finalidade de cada parte da página.

### 📊 Principais elementos

| Elemento | Função |
|---|---|
| `<header>` | Cabeçalho |
| `<nav>` | Navegação |
| `<main>` | Conteúdo principal |
| `<section>` | Seção |
| `<article>` | Conteúdo independente |
| `<footer>` | Rodapé |

### 💻 Exemplo

```html
<header>

    <h1>Meu Site</h1>

</header>

<nav>

    <a href="/">Início</a>
    <a href="/sobre">Sobre</a>

</nav>

<main>

    <section>

        <h2>Sobre o projeto</h2>

        <p>
            Conteúdo da seção.
        </p>

    </section>

</main>

<footer>

    <p>© 2026 Meu Site</p>

</footer>
```

---

# 9️⃣ Links e navegação 🔗

Os links permitem conectar diferentes páginas de um site.

```html
<a href="/cursos">
    Conheça nossos cursos
</a>
```

### ❌ Evite textos genéricos

```html
<a href="/cursos">
    Clique aqui
</a>
```

### ✅ Prefira textos descritivos

```html
<a href="/cursos">
    Conheça nossos cursos
</a>
```

O texto do link deve ajudar o usuário a compreender **para onde ele será direcionado**.

---

## 🧭 Links internos

Os links internos conectam diferentes páginas do mesmo site.

```text
Início
 │
 ├── Sobre
 │
 ├── Cursos
 │    ├── HTML
 │    └── CSS
 │
 └── Contato
```

### 💻 Exemplo

```html
<nav>

    <a href="/">
        Início
    </a>

    <a href="/cursos/html">
        Curso de HTML
    </a>

    <a href="/cursos/css">
        Curso de CSS
    </a>

</nav>
```

---

# 🔟 Imagens e SEO 🖼️

As imagens também podem contribuir para a compreensão do conteúdo.

O atributo `alt` fornece uma descrição alternativa da imagem.

### ❌ Sem `alt`

```html
<img src="notebook.jpg">
```

### ✅ Com `alt`

```html
<img
    src="notebook.jpg"
    alt="Notebook utilizado para desenvolvimento web"
>
```

O texto alternativo deve **descrever o conteúdo ou função da imagem**, sem exagerar no uso de palavras-chave.

---

## 📐 `width` e `height`

Também podemos informar as dimensões da imagem.

```html
<img
    src="notebook.jpg"
    alt="Notebook utilizado para desenvolvimento web"
    width="800"
    height="450"
>
```

Definir as dimensões ajuda o navegador a reservar espaço para a imagem durante o carregamento.

---

# 1️⃣1️⃣ URL e Canonical 🔗

URLs claras ajudam usuários a compreender o conteúdo da página.

### ❌ URL pouco descritiva

```text
site.com/pagina?id=123
```

### ✅ URL mais descritiva

```text
site.com/cursos/html
```

## 🔗 Canonical

A tag `canonical` indica a URL principal de uma página.

```html
<link
    rel="canonical"
    href="https://exemplo.com/cursos/html"
>
```

Ela pode ser utilizada quando existem diferentes URLs que apresentam conteúdo igual ou muito semelhante.

---

# 1️⃣2️⃣ Indexação e Robots 🤖

Por padrão, uma página pode ser disponibilizada para indexação pelos mecanismos de busca.

Podemos utilizar a meta tag `robots` para fornecer instruções relacionadas à indexação.

### 📌 Indexação

```html
<meta
    name="robots"
    content="index, follow"
>
```

### 🚫 Não indexar

```html
<meta
    name="robots"
    content="noindex"
>
```

O `noindex` pode ser utilizado em páginas que não devem aparecer nos resultados de pesquisa.

> 💡 A utilização de `noindex` deve ser feita com cuidado, pois impede a página de ser indexada.

---

# 🧪 1️⃣3️⃣ Exemplo completo

```html
<!DOCTYPE html>

<html lang="pt-BR">

<head>

    <meta charset="UTF-8">

    <!-- Título claro e relacionado ao conteúdo -->
    <title>Curso de HTML | Desenvolvimento Web</title>

    <!-- Descrição da página -->
    <meta
        name="description"
        content="Aprenda HTML e boas práticas para desenvolvimento web."
    >

    <!-- Configuração para dispositivos móveis -->
    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <!-- URL principal da página -->
    <link
        rel="canonical"
        href="https://exemplo.com.br/curso-html"
    >

</head>

<body>

    <header>

        <h1>Curso de HTML</h1>

    </header>

    <nav>

        <a href="/">
            Início
        </a>

        <a href="/curso-html">
            Curso de HTML
        </a>

        <a href="/contato">
            Contato
        </a>

    </nav>

    <main>

        <section>

            <h2>Aprenda HTML</h2>

            <p>
                Aprenda os fundamentos do HTML e desenvolva
                páginas web utilizando boas práticas.
            </p>

            <img
                src="html.jpg"
                alt="Exemplo de código HTML"
                width="800"
                height="450"
            >

        </section>

        <section>

            <h2>Conteúdos</h2>

            <h3>Estrutura HTML</h3>

            <p>
                Aprenda a criar a estrutura de documentos HTML.
            </p>

            <h3>Elementos e atributos</h3>

            <p>
                Conheça os principais elementos e atributos HTML.
            </p>

        </section>

    </main>

    <footer>

        <p>
            © 2026 - Curso de HTML
        </p>

    </footer>

</body>

</html>
```

---

# 🔎 Analisando o exemplo

| Elemento | Aplicação |
|---|---|
| `lang="pt-BR"` 🌎 | Define o idioma |
| `<title>` 🏷️ | Define um título descritivo |
| `description` 📝 | Descreve o conteúdo |
| `viewport` 📱 | Permite adaptação para dispositivos |
| `canonical` 🔗 | Define a URL principal |
| `<h1>` | Define o assunto principal |
| `<h2>` | Organiza as seções |
| `<h3>` | Organiza subseções |
| `<header>` | Estrutura o cabeçalho |
| `<nav>` | Estrutura a navegação |
| `<main>` | Define o conteúdo principal |
| `<section>` | Organiza o conteúdo |
| `<footer>` | Estrutura o rodapé |
| `alt` ♿ | Descreve a imagem |
| `width` / `height` 📐 | Define dimensões da imagem |
| Links descritivos 🔗 | Facilita a compreensão dos destinos |

---

# 📚 1️⃣4️⃣ Resumo

| Boa prática | Exemplo |
|---|---|
| 🌎 Definir idioma | `<html lang="pt-BR">` |
| 🏷️ Criar título | `<title>` |
| 📝 Descrever a página | `meta description` |
| 📱 Adaptar para dispositivos | `viewport` |
| 🔎 Organizar conteúdo | `<h1>`, `<h2>`, `<h3>` |
| 🧩 Utilizar semântica | `<main>`, `<section>`, `<article>` |
| 🔗 Criar links descritivos | `<a href="">` |
| 🖼️ Descrever imagens | `alt` |
| 📐 Definir dimensões | `width`, `height` |
| 🔗 Definir URL principal | `canonical` |
| 🤖 Controlar indexação | `robots` |

---

# 🚀 Exercício

Crie um pequeno site utilizando **HTML e CSS** sobre um tema de sua escolha.

O site deverá possuir pelo menos **três páginas interligadas**, utilizando uma estrutura de navegação clara.

Durante o desenvolvimento, aplique as boas práticas de SEO apresentadas neste tutorial, utilizando título, descrição, idioma, viewport, headings, HTML semântico, links internos e imagens com texto alternativo.

Após finalizar uma primeira versão do site, utilize uma **ferramenta de análise de PageRank ou SEO** para avaliar a página. Registre o resultado e identifique pontos que podem ser melhorados.

Em seguida, faça melhorias no site com base na análise realizada e execute novamente a ferramenta. Compare os resultados **antes e depois das alterações**.

### 📋 Entrega

O grupo deverá entregar:

- [ ] Arquivos HTML
- [ ] Arquivos CSS
- [ ] Imagens utilizadas
- [ ] Estrutura de navegação entre as páginas
- [ ] Resultado da primeira análise
- [ ] Melhorias realizadas
- [ ] Resultado da segunda análise
- [ ] Comparação entre os resultados
- [ ] Breve conclusão sobre as melhorias realizadas

### 🎯 Desafio

> **O objetivo não é apenas criar um site bonito. É criar uma página bem estruturada, acessível e compreensível para usuários e mecanismos de busca.**
