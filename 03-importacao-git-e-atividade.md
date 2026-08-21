# Aula 03 — Importação, Git e Atividade Prática

## 1. Buscando projetos prontos

Nem sempre é necessário começar uma aplicação do zero.

Projetos disponibilizados pela comunidade podem servir como:

- Referência de arquitetura.
- Base para novos projetos.
- Demonstração de boas práticas.
- Template inicial.
- Fonte de componentes e soluções.

## 2. Onde pesquisar

### GitHub

Permite pesquisar repositórios desenvolvidos com diferentes tecnologias.

Para clonar um repositório:

```bash
git clone <url>
```

Depois:

```bash
cd <pasta-do-projeto>
npm install
```

### Vercel

Possui templates de projetos que podem ser utilizados como ponto de partida.

### CodeSandbox

Permite pesquisar e experimentar templates diretamente no navegador.

---

# 3. Importando e executando um projeto

Fluxo recomendado:

```text
Pesquisar projeto
      ↓
Escolher um template
      ↓
Clonar ou baixar
      ↓
Entrar na pasta
      ↓
Instalar dependências
      ↓
Executar localmente
      ↓
Analisar estrutura
      ↓
Modificar código
      ↓
Versionar com Git
      ↓
Enviar para GitHub
```

## Comandos básicos

```bash
git clone <url>
cd <projeto>
npm install
npm run dev
```

> O comando para iniciar o projeto pode variar conforme o `package.json`.

---

# 4. Versionando o projeto

Depois de realizar alterações:

```bash
git status
git add .
git commit -m "feat: primeira alteração"
```

Para conectar ao GitHub:

```bash
git remote add origin <url-do-repositorio>
git branch -M main
git push -u origin main
```

## Fluxo de trabalho

```text
Alterar código
      ↓
git status
      ↓
git add .
      ↓
git commit
      ↓
git push
```

---

# 5. Atividade prática

## Parte 1 — React

Crie um projeto utilizando React.

### Faça:

- Criar o projeto.
- Executar localmente.
- Alterar a interface inicial.
- Criar pelo menos uma alteração visual.
- Versionar com Git.
- Criar um repositório no GitHub.
- Realizar o `push`.

---

## Parte 2 — Angular

Crie um projeto utilizando Angular.

### Faça:

- Criar o projeto.
- Executar localmente.
- Alterar a interface inicial.
- Criar pelo menos uma alteração visual.
- Versionar com Git.
- Criar um repositório no GitHub.
- Realizar o `push`.

---

## Parte 3 — Vue

Crie um projeto utilizando Vue.

### Faça:

- Criar o projeto.
- Executar localmente.
- Alterar a interface inicial.
- Criar pelo menos uma alteração visual.
- Versionar com Git.
- Criar um repositório no GitHub.
- Realizar o `push`.

---

## Parte 4 — Importação de template

Escolha **um dos frameworks estudados** e encontre um projeto pronto.

### Faça:

1. Pesquise um template no GitHub, Vercel ou CodeSandbox.
2. Importe ou clone o projeto.
3. Instale as dependências.
4. Execute localmente.
5. Analise sua estrutura.
6. Faça alterações no projeto.
7. Versione as alterações.
8. Publique o projeto em um repositório no GitHub.

---

# 6. Checklist de entrega

### Projeto React

- [ ] Projeto criado.
- [ ] Aplicação executando.
- [ ] Interface modificada.
- [ ] Git configurado.
- [ ] Repositório no GitHub.
- [ ] Commit realizado.

### Projeto Angular

- [ ] Projeto criado.
- [ ] Aplicação executando.
- [ ] Interface modificada.
- [ ] Git configurado.
- [ ] Repositório no GitHub.
- [ ] Commit realizado.

### Projeto Vue

- [ ] Projeto criado.
- [ ] Aplicação executando.
- [ ] Interface modificada.
- [ ] Git configurado.
- [ ] Repositório no GitHub.
- [ ] Commit realizado.

### Projeto importado

- [ ] Template localizado.
- [ ] Projeto importado.
- [ ] Dependências instaladas.
- [ ] Aplicação executando.
- [ ] Código modificado.
- [ ] Git configurado.
- [ ] Repositório publicado.

---

# 7. Objetivo da atividade

Ao concluir a atividade, o aluno deverá demonstrar que consegue **criar, executar, modificar e versionar projetos front-end utilizando diferentes tecnologias**, além de compreender como projetos existentes podem ser reutilizados como ponto de partida para novas aplicações.

## Conclusão

O desenvolvimento com frameworks front-end permite trabalhar com estruturas organizadas, componentes reutilizáveis, ferramentas de automação e integração com diferentes recursos do ecossistema JavaScript.

Mais importante do que apenas criar um projeto é compreender o fluxo completo:

**criar → executar → modificar → versionar → publicar.**
