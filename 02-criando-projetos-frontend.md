# Aula 03 — Criando Projetos Front-end

## 1. Pré-requisito: Node.js

O Node.js permite executar JavaScript fora do navegador e fornece o ambiente necessário para utilizar ferramentas do ecossistema front-end.

Verifique a instalação:

```bash
node --version
npm --version
```

## 2. NPM

O **NPM (Node Package Manager)** é utilizado para instalar e gerenciar dependências.

O arquivo `package.json` registra informações importantes do projeto, incluindo:

- Dependências.
- Scripts.
- Nome e versão do projeto.
- Configurações do projeto.

Para instalar as dependências:

```bash
npm install
```

---

# 3. React

## Características

- Flexível.
- Baseado em componentes.
- Grande ecossistema.
- Suporte a Hooks.
- Utilização de JSX.
- Virtual DOM.

## Criando um projeto

```bash
npx create-react-app meu-projeto-react
cd meu-projeto-react
code .
npm start
```

## Estrutura básica

```text
meu-projeto-react/
├── node_modules/
├── public/
├── src/
├── .gitignore
├── package.json
└── package-lock.json
```

Arquivos importantes:

- `src/index.js` → ponto de entrada.
- `src/App.js` → componente principal.
- `src/App.css` → estilos do componente.
- `src/index.css` → estilos globais.

---

# 4. Angular

## Características

- Framework completo.
- TypeScript nativo.
- Roteamento.
- HTTP Client.
- Injeção de dependências.
- CLI para criação e gerenciamento do projeto.

## Criando um projeto

```bash
npm install -g @angular/cli
ng new meu-app-angular
cd meu-app-angular
code .
ng serve
```

## Conceitos fundamentais

- **Componentes** → estrutura da interface.
- **Serviços** → lógica reutilizável.
- **Data Binding** → comunicação entre dados e interface.
- **Injeção de Dependência** → gerenciamento de serviços.
- **Roteamento** → navegação entre views.

---

# 5. Vue

## Características

- Framework progressivo.
- Sistema de reatividade.
- Componentes reutilizáveis.
- Single-File Components (`.vue`).
- Curva de aprendizado acessível.
- Performance otimizada.

## Criando um projeto

```bash
npm create vue@latest
cd meu-projeto-vue
npm install
code .
npm run dev
```

## Estrutura básica

```text
meu-projeto-vue/
├── node_modules/
├── public/
├── src/
├── .vscode/
├── .gitignore
├── package.json
├── package-lock.json
└── vite.config.js
```

Dentro de `src`:

```text
src/
├── assets/
├── components/
├── App.vue
└── main.js
```

- `components/` → componentes reutilizáveis.
- `App.vue` → componente raiz.
- `main.js` → ponto de entrada.
- `assets/` → recursos processados pelo Vite.

---

# 6. Next.js

O Next.js amplia o ecossistema React com recursos voltados à construção de aplicações web completas.

## Criando um projeto

```bash
npx create-next-app@latest meu-projeto
cd meu-projeto
code .
npm run dev
```

No uso do **App Router**, a pasta `app` organiza páginas, layouts, estilos e rotas da aplicação.

---

# 7. Comparação rápida

| Tecnologia | Criação | Execução |
|---|---|---|
| React | `npx create-react-app` | `npm start` |
| Angular | `ng new` | `ng serve` |
| Vue | `npm create vue@latest` | `npm run dev` |
| Next.js | `npx create-next-app@latest` | `npm run dev` |

## Resultado esperado

Ao final desta etapa, o aluno deve conseguir:

1. Criar um projeto front-end.
2. Instalar suas dependências.
3. Abrir o projeto no VS Code.
4. Executar o servidor local.
5. Identificar a estrutura básica de arquivos.
