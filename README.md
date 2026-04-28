# Java.Dev Landing Page

Landing page oficial da comunidade **Java.Dev**, um projeto criado para divulgar o servidor no Discord e apresentar o objetivo da comunidade para novos participantes.

A proposta do Java.Dev é ser uma comunidade gratuita, feita **por iniciante para iniciante**, com foco em estudos, grupos de estudo, troca de dúvidas, dicas de cursos gratuitos, vídeos, vagas, networking e evolução na área de desenvolvimento back-end com Java.

---

## Sobre o projeto

A landing page foi criada para explicar de forma clara o que é a comunidade **Java.Dev** e incentivar novos estudantes a entrarem no servidor do Discord.

O projeto não tem como objetivo ser uma plataforma de cursos ou vender conteúdo. A ideia principal é reunir pessoas que estão aprendendo programação para que possam estudar juntas, compartilhar materiais, tirar dúvidas e crescer em comunidade.

---

## Objetivo da comunidade Java.Dev

O **Java.Dev** nasceu com uma proposta simples: criar um ambiente onde iniciantes possam se ajudar durante a jornada de aprendizado em programação.

A comunidade tem como foco:

- montar grupos de estudo;
- compartilhar cursos gratuitos;
- indicar vídeos e materiais úteis;
- tirar dúvidas sobre programação;
- divulgar vagas e oportunidades;
- incentivar networking entre estudantes e desenvolvedores;
- apoiar quem está começando na carreira de tecnologia;
- fortalecer os estudos em Java e desenvolvimento back-end.

---

## Para quem é essa comunidade?

A comunidade é indicada para pessoas que:

- estão começando na programação;
- estudam Java;
- querem aprender lógica de programação;
- querem evoluir em orientação a objetos;
- têm interesse em Spring Boot;
- querem criar APIs REST;
- estão estudando banco de dados;
- querem praticar com projetos reais;
- buscam networking com outros iniciantes;
- querem compartilhar dúvidas, erros, aprendizados e evolução.

---

## Tecnologias utilizadas

Este projeto foi desenvolvido com tecnologias simples e acessíveis:

- **HTML5**
- **CSS3**
- **JavaScript**

O projeto não utiliza frameworks, bibliotecas externas ou processo de build. Isso facilita a manutenção e permite que qualquer iniciante consiga entender, editar e publicar a página.

---

## Funcionalidades da página

A landing page possui:

- layout responsivo;
- design escuro com estilo neon;
- identidade visual baseada na marca Java.Dev;
- botão para entrar no Discord;
- botão para acessar o LinkedIn do autor;
- seção explicando o objetivo da comunidade;
- seção sobre a proposta do projeto;
- trilha de estudos sugerida;
- seção para apresentar o autor;
- chamada final para entrar na comunidade;
- contador simples de acessos.

---

## Link da comunidade

Entre na comunidade Java.Dev pelo Discord:

[Entrar no Discord](https://discord.gg/PPUaYePqWp)

---

## Autor

Projeto criado por **Ricardo Rodrigues Santana**.

Ricardo é estudante de Engenharia de Software e está em transição de carreira para desenvolvimento back-end, com foco em Java, Spring Boot, APIs REST e banco de dados.

LinkedIn:

[linkedin.com/in/ricardo-r-santana](https://www.linkedin.com/in/ricardo-r-santana/)

---

## Como executar o projeto localmente

Como o projeto é feito apenas com HTML, CSS e JavaScript, não é necessário instalar dependências.

### Passo 1: clonar o repositório

```bash
git clone https://github.com/Ric-ardo28/java-dev-landing-page.git
```

### Passo 2: acessar a pasta do projeto

```bash
cd java-dev-landing-page
```

### Passo 3: abrir o arquivo no navegador

Abra o arquivo `index.html` diretamente no navegador.

Também é possível usar a extensão **Live Server** no VS Code para visualizar a página localmente com atualização automática.

---

## Estrutura do projeto

```text
java-dev-landing-page/
│
├── index.html
└── README.md
```

### `index.html`

Arquivo principal da landing page. Contém a estrutura HTML, os estilos CSS e o JavaScript do contador de acessos.

### `README.md`

Arquivo de documentação do projeto.

---

## Como hospedar na Vercel

Este projeto pode ser hospedado facilmente na Vercel.

### Passo 1: acessar a Vercel

Acesse:

[https://vercel.com](https://vercel.com)

### Passo 2: conectar com o GitHub

Faça login na Vercel usando sua conta do GitHub.

### Passo 3: importar o projeto

Clique em:

```text
Add New Project
```

Depois selecione o repositório:

```text
java-dev-landing-page
```

### Passo 4: configurar o deploy

Como o projeto é estático, você pode usar as configurações padrão.

Caso a Vercel peça configuração manual, use:

```text
Framework Preset: Other
Build Command: deixar vazio
Output Directory: deixar vazio ou ./
Install Command: deixar vazio
```

### Passo 5: publicar

Clique em:

```text
Deploy
```

Após o deploy, a Vercel vai gerar um link público parecido com:

```text
https://java-dev-landing-page.vercel.app
```

---

## Contador de acessos

A página possui um contador simples de acessos.

O contador tenta usar um serviço externo gratuito:

```text
https://api.countapi.xyz
```

Caso o serviço externo não esteja disponível, o projeto usa um contador local com `localStorage` como alternativa.

### Observação importante

O contador local não conta visitas globais reais. Ele conta apenas acessos salvos no navegador da pessoa que está visitando a página.

Para um contador mais profissional, é recomendado usar uma ferramenta como:

- Vercel Analytics;
- Google Analytics;
- Plausible;
- GoatCounter.

---

## Melhorias futuras

Algumas ideias para evoluir o projeto:

- adicionar favicon personalizado;
- adicionar imagem de preview para compartilhamento em redes sociais;
- criar uma seção com cursos gratuitos recomendados;
- adicionar depoimentos de membros da comunidade;
- criar uma página separada para roadmap de estudos;
- adicionar formulário para sugestões de cursos e materiais;
- integrar Vercel Analytics;
- melhorar o SEO da página;
- adicionar animações leves;
- criar uma versão com React no futuro.

---

## Status do projeto

Projeto em desenvolvimento.

A primeira versão da landing page já apresenta a proposta da comunidade, botões de acesso, informações do autor e contador de visitas.

---

## Licença

Este projeto pode ser usado como base de estudo e aprendizado.

Caso utilize ou adapte, mantenha os créditos ao autor original.

---

## Mensagem final

O Java.Dev é uma comunidade feita para quem está começando e quer evoluir junto com outras pessoas.

A ideia é simples: ninguém precisa estudar sozinho.
