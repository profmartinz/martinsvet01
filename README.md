# 🐾 MartinsVet — Pet Shop & Clínica Veterinária

Projeto desenvolvido para os alunos do **2º período** da disciplina **Desenvolvimento Web para IA**, da **Faculdade PIT**.

Este projeto marca o primeiro contato da turma com a criação de páginas web utilizando **HTML (HyperText Markup Language)**, trabalhando conceitos fundamentais de estruturação de páginas, elementos semânticos, links, formulários e organização de conteúdo.

---

## 📚 Sobre o projeto

A **MartinsVet** é uma página web fictícia desenvolvida para representar um **Pet Shop e uma Clínica Veterinária**.

Nesta primeira etapa, o objetivo é trabalhar exclusivamente a **estrutura HTML da página**, sem utilização de CSS ou JavaScript.

O projeto apresenta:

* 🏠 Página inicial
* 🐾 Informações sobre a empresa
* 🩺 Serviços veterinários
* 🛍️ Serviços de Pet Shop
* 📋 Formulário de contato
* 📱 Estrutura preparada para diferentes tamanhos de tela
* 🔗 Navegação interna através de links

---

## 🛠️ Tecnologias utilizadas

Neste primeiro projeto estamos utilizando:

* **HTML5**
* **Visual Studio Code**
* **GitHub**

> 🚧 CSS e JavaScript serão utilizados nas próximas etapas da disciplina para estilização e implementação de funcionalidades.

---

# 💻 Como baixar o projeto pelo GitHub

## 1. Instale o Visual Studio Code

Acesse o site oficial:

https://code.visualstudio.com/

Baixe a versão correspondente ao seu sistema operacional e faça a instalação normalmente.

---

## 2. Instale o Git

Para baixar projetos do GitHub diretamente pelo VS Code, recomendamos também a instalação do **Git**.

Acesse:

https://git-scm.com/downloads

Baixe e instale o Git utilizando as opções padrão do instalador.

Depois da instalação, você pode verificar se o Git foi instalado corretamente.

Abra o **Prompt de Comando**, PowerShell ou terminal e execute:

```bash
git --version
```

Se aparecer algo semelhante a:

```text
git version 2.x.x
```

o Git está instalado corretamente.

---

# 📥 3. Baixe o projeto do GitHub

No GitHub, acesse o repositório da disciplina.

Clique no botão:

**Code → HTTPS**

Copie o endereço do repositório.

Exemplo:

```text
https://github.com/seu-usuario/martinsvet.git
```

> ⚠️ Utilize o endereço do repositório disponibilizado pelo professor.

---

# 📂 4. Clone o projeto pelo VS Code

Abra o **Visual Studio Code**.

Na tela inicial, selecione:

**Clone Git Repository**

Ou utilize o atalho:

```text
Ctrl + Shift + P
```

Digite:

```text
Git: Clone
```

Selecione:

**Git: Clone**

Cole o endereço do repositório:

```text
https://github.com/seu-usuario/martinsvet.git
```

Pressione **Enter**.

---

# 📁 5. Escolha onde salvar o projeto

O VS Code solicitará que você escolha uma pasta para armazenar o projeto.

Escolha um local de fácil acesso, por exemplo:

```text
Documentos
```

O VS Code fará o download dos arquivos do GitHub.

Ao finalizar, aparecerá a opção:

**Open**

Clique nela para abrir o projeto.

---

# 🌐 6. Abra o arquivo HTML

No explorador de arquivos do VS Code, localize:

```text
index.html
```

Clique sobre o arquivo para abrir o código.

A estrutura principal será semelhante a:

```html
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MartinsVet - Pet Shop & Clínica Veterinária</title>
</head>

<body>

    <!-- Conteúdo da página -->

</body>

</html>
```

---

# 🚀 7. Execute o projeto

Existem algumas maneiras de visualizar uma página HTML.

### Opção 1 — Abrir diretamente no navegador

Localize o arquivo:

```text
index.html
```

Clique com o botão direito sobre ele e escolha:

**Abrir com → Google Chrome**

ou outro navegador de sua preferência.

---

### Opção 2 — Utilizando o Live Server

Uma opção muito prática durante o desenvolvimento é utilizar a extensão **Live Server**.

No VS Code:

1. Clique em **Extensions** no menu lateral.
2. Pesquise por:

```text
Live Server
```

3. Instale a extensão.
4. Abra o arquivo `index.html`.
5. Clique com o botão direito no código.
6. Selecione:

**Open with Live Server**

O navegador será aberto automaticamente.

Sempre que você salvar uma alteração no HTML, a página poderá ser atualizada automaticamente.

---

# 🧠 O que estamos aprendendo?

Neste primeiro projeto estamos trabalhando conceitos fundamentais de HTML5.

### Estrutura básica

```html
<!DOCTYPE html>
<html>
<head>
</head>

<body>
</body>
</html>
```

### Títulos

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Outro título</h3>
```

### Parágrafos

```html
<p>Este é um parágrafo.</p>
```

### Links

```html
<a href="#sobre">Sobre</a>
```

### Listas

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

### Formulários

```html
<form>

    <input type="text">
    <input type="email">

    <textarea></textarea>

    <button type="submit">
        Enviar
    </button>

</form>
```

### Organização semântica

Também estamos começando a trabalhar com elementos que ajudam a organizar semanticamente uma página:

```html
<header>
<nav>
<main>
<section>
<footer>
```

---

# 📌 Estrutura do projeto

Inicialmente, o projeto possui uma estrutura simples:

```text
martinsvet/
│
├── index.html
│
└── README.md
```

À medida que o projeto evoluir durante a disciplina, novos arquivos e pastas serão adicionados.

Por exemplo:

```text
martinsvet/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── README.md
```

---

# 🎯 Próximas etapas

O projeto será desenvolvido gradualmente durante a disciplina.

### Etapa 1 — HTML

✅ Estrutura da página
✅ Títulos e parágrafos
✅ Links
✅ Listas
✅ Formulários
✅ Elementos semânticos

### Etapa 2 — CSS

🔲 Cores
🔲 Tipografia
🔲 Espaçamentos
🔲 Layout
🔲 Responsividade
🔲 Animações

### Etapa 3 — JavaScript

🔲 Interatividade
🔲 Manipulação do DOM
🔲 Validação de formulários
🔲 Eventos
🔲 Funcionalidades dinâmicas

### Etapa 4 — Integração com IA

🔲 Consumo de APIs
🔲 Integração com serviços de IA
🔲 Funcionalidades inteligentes
🔲 Aplicações práticas de Inteligência Artificial na Web

---

# 👨‍💻 Atividade para os alunos

Após baixar o projeto, abra o `index.html` e faça algumas alterações no código.

Experimente:

1. Alterar o nome da clínica.
2. Modificar o texto da seção **Sobre Nós**.
3. Adicionar um novo serviço.
4. Alterar os textos dos campos do formulário.
5. Adicionar uma nova opção ao menu.
6. Criar uma nova seção na página.

### 🚀 Desafio

Tente adicionar uma nova seção chamada:

```text
Nossos Profissionais
```

Inclua pelo menos **três profissionais fictícios**, utilizando os conhecimentos de HTML apresentados em aula.

---

# 🎓 Disciplina

**Desenvolvimento Web para IA**

**2º período — Faculdade PIT**

Projeto desenvolvido para fins **educacionais e acadêmicos**.

---

## 👨‍🏫 Professor

**Tiago Martins**

Faculdade PIT — 2026

---

> 💡 **Dica:** Não tenha medo de modificar o código. Errar faz parte do processo de aprendizagem. Experimente, altere, salve e observe o que acontece no navegador!
