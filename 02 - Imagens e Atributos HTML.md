# 🖼️ Imagens e Atributos HTML

---

## 🎯 Objetivo

Neste tutorial, vamos aprender como inserir imagens em páginas HTML e como utilizar atributos para fornecer informações adicionais aos elementos.

Também vamos aprender a visualizar o código HTML de uma página utilizando as ferramentas do navegador.

---

## 🗺️ Conteúdo

| # | Conteúdo | Principal conceito |
|---|---|---|
| 1️⃣ | Imagens HTML | `<img>` |
| 2️⃣ | Código-fonte | `CTRL + U` |
| 3️⃣ | Inspecionar | Ferramentas do navegador |
| 4️⃣ | Atributos HTML | `nome="valor"` |
| 5️⃣ | `href` e `src` | Endereços |
| 6️⃣ | Dimensões e `alt` | Imagens |
| 7️⃣ | Outros atributos | `style`, `lang`, `title` |
| 8️⃣ | Boas práticas | Organização |
| 9️⃣ | Exemplo completo | Aplicação |
| 🔟 | Exercício | Prática |

---

# 1️⃣ Imagens HTML

As imagens são inseridas utilizando a tag `<img>`.

O atributo `src` indica o caminho da imagem, enquanto `alt`, `width` e `height` fornecem informações adicionais.

### 🧩 Estrutura

```html
<img
    src="imagem.jpg"
    alt="Descrição da imagem"
    width="300"
    height="200"
>
```

### 📊 Principais atributos

| Atributo | Função |
|---|---|
| `src` 🖼️ | Define o caminho da imagem |
| `alt` ♿ | Define o texto alternativo |
| `width` 📏 | Define a largura |
| `height` 📐 | Define a altura |

---

# 2️⃣ Como visualizar o código HTML 🔎

É possível visualizar o código HTML utilizado para construir uma página diretamente pelo navegador.

## 👀 Visualizar código-fonte

Utilize:

```text
CTRL + U
```

Também é possível:

1. 🖱️ Clicar com o botão direito na página.
2. 🔎 Selecionar **Exibir código-fonte da página**.
3. 🌐 Abrir a nova aba.
4. 💻 Analisar o código HTML.

---

## 🛠️ Inspecionar elementos

1. 🖱️ Clique com o botão direito sobre um elemento.
2. 🔎 Selecione **Inspecionar**.
3. 🧩 Observe o HTML do elemento.
4. 🎨 Observe também o CSS aplicado.
5. ✏️ Faça alterações temporárias para testar.

### 📌 Comparação

| Ferramenta | Utilização |
|---|---|
| `CTRL + U` | Visualizar o código-fonte |
| Inspecionar | Analisar elementos individualmente |
| Elements | Visualizar estrutura HTML |
| Styles | Visualizar regras CSS |

---

# 3️⃣ Atributos HTML

Os atributos fornecem informações adicionais aos elementos HTML.

Eles são escritos na tag de abertura.

### 🧩 Estrutura

```html
<tag atributo="valor">
```

### 💻 Exemplo

```html
<a href="https://www.google.com">
    Google
</a>
```

### 📊 Regras

| Regra | Descrição |
|---|---|
| 🧩 Elementos | Podem possuir atributos |
| 📍 Localização | Atributos ficam na tag de abertura |
| 🔤 Formato | `nome="valor"` |
| 🔗 Função | Fornecem informações adicionais |

---

# 4️⃣ O atributo `href` 🔗

O atributo `href` é utilizado na tag `<a>` para indicar o endereço de destino de um link.

```html
<a href="https://www.google.com">
    Google
</a>
```

| Parte | Função |
|---|---|
| `<a>` | Elemento |
| `href` | Atributo |
| URL | Destino |
| Texto | Conteúdo do link |

---

# 5️⃣ O atributo `src` 🖼️

O atributo `src` indica o caminho de um recurso utilizado pelo elemento.

```html
<img src="img_girl.jpg">
```

## 🌐 URL absoluta

```html
<img src="https://www.exemplo.com/images/imagem.jpg">
```

## 📁 URL relativa

```html
<img src="img_girl.jpg">
```

Também podemos utilizar pastas:

```html
<img src="images/img_girl.jpg">
```

> 💡 **Dica:** utilizar caminhos relativos facilita a organização dos arquivos do projeto.

---

# 6️⃣ `width`, `height` e `alt` 📐

Os atributos `width` e `height` permitem definir as dimensões da imagem.

O atributo `alt` fornece uma descrição alternativa.

```html
<img
    src="img_girl.jpg"
    alt="Girl with a jacket"
    width="500"
    height="600"
>
```

| Atributo | Função |
|---|---|
| `width` 📏 | Largura |
| `height` 📐 | Altura |
| `alt` ♿ | Descrição alternativa |

### ♿ Texto alternativo

O `alt` pode ser utilizado quando a imagem não pode ser exibida e também auxilia usuários que utilizam leitores de tela.

```html
<img
    src="imagem_inexistente.jpg"
    alt="Descrição da imagem"
>
```

---

# 7️⃣ Outros atributos HTML

## 🎨 `style`

Permite adicionar estilos diretamente ao elemento.

```html
<p style="color:red;">
    Este é um texto vermelho.
</p>
```

## 🌎 `lang`

Define o idioma da página.

```html
<html lang="pt-BR">
```

## 💬 `title`

Fornece informações adicionais sobre um elemento.

```html
<p title="Informação adicional">
    Passe o mouse sobre este texto.
</p>
```

### 📊 Resumo

| Atributo | Utilização |
|---|---|
| `style` 🎨 | Define estilos |
| `lang` 🌎 | Define o idioma |
| `title` 💬 | Fornece informação adicional |

---

# 8️⃣ Boas práticas 🔤

## 🔤 Utilize letras minúsculas

### ✅ Recomendado

```html
<a href="https://www.exemplo.com">
    Meu Link
</a>
```

### ⚠️ Evitar

```html
<A HREF="https://www.exemplo.com">
    Meu Link
</A>
```

---

## `" "` Utilize aspas

### ✅ Recomendado

```html
<a href="https://www.exemplo.com">
    Meu Link
</a>
```

### ❌ Evitar

```html
<a href=https://www.exemplo.com>
    Meu Link
</a>
```

Quando o valor possui espaços, as aspas são especialmente importantes.

```html
<p title="Descrição da página">
```

---

# 9️⃣ Aspas simples e duplas

Os dois formatos podem ser utilizados.

### 🔵 Aspas duplas

```html
<p title="Descrição do elemento">
    Texto
</p>
```

### 🟢 Aspas simples

```html
<p title='Descrição do elemento'>
    Texto
</p>
```

Quando o valor possui aspas, podemos utilizar o outro tipo.

```html
<p title='John "ShotGun" Nelson'>
    Texto
</p>
```

Ou:

```html
<p title="John 'ShotGun' Nelson">
    Texto
</p>
```

---

# 🧪 Exemplo completo

```html
<!DOCTYPE html>

<html lang="pt-BR">

<body>

    <h1>Minha Página</h1>

    <p title="Texto introdutório">
        Bem-vindo à minha página HTML.
    </p>

    <h2>Imagem</h2>

    <img
        src="imagem.jpg"
        alt="Imagem de exemplo"
        width="300"
        height="200"
    >

    <h2>Link</h2>

    <a href="https://www.google.com">
        Acessar Google
    </a>

</body>

</html>
```

---

# 🔎 Analisando o exemplo

| Elemento | Atributo | Função |
|---|---|---|
| `<html>` | `lang` | Define o idioma |
| `<p>` | `title` | Adiciona informação adicional |
| `<img>` | `src` | Define o caminho |
| `<img>` | `alt` | Define a descrição |
| `<img>` | `width` | Define a largura |
| `<img>` | `height` | Define a altura |
| `<a>` | `href` | Define o destino |

---

# 📚 Resumo

| Atributo | Elemento | Função |
|---|---|---|
| `href` 🔗 | `<a>` | Define o destino |
| `src` 🖼️ | `<img>` | Define o caminho |
| `width` 📏 | `<img>` | Define a largura |
| `height` 📐 | `<img>` | Define a altura |
| `alt` ♿ | `<img>` | Define texto alternativo |
| `style` 🎨 | Elementos HTML | Define estilos |
| `lang` 🌎 | `<html>` | Define o idioma |
| `title` 💬 | Elementos HTML | Informação adicional |

---

# 🚀 Exercício

Crie uma página HTML que contenha:

| Requisito | Elemento/Atributo |
|---|---|
| 📄 HTML5 | `<!DOCTYPE html>` |
| 🌎 Idioma | `lang="pt-BR"` |
| 🏷️ Título | `<h1>` |
| 📝 Parágrafo | `<p>` |
| 🔗 Link | `<a>` + `href` |
| 🖼️ Imagem | `<img>` |
| 📁 Caminho | `src` |
| ♿ Descrição | `alt` |
| 📏 Largura | `width` |
| 📐 Altura | `height` |
| 💬 Informação adicional | `title` |

### 🎯 Desafio

1. Abra o arquivo no navegador.
2. Pressione `CTRL + U`.
3. Observe o código-fonte.
4. Volte para a página.
5. Clique com o botão direito sobre um elemento.
6. Selecione **Inspecionar**.
7. Identifique os atributos utilizados.
