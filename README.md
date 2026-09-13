<div align="center">

# 🔷 LabMatch

### Encontra o laboratório que combina com sua atividade.

**Uma plataforma pensada para facilitar a busca, descoberta e reserva de laboratórios no ambiente acadêmico.**

<br>

<a href="https://labmatch-eosin.vercel.app">
  <img src="https://img.shields.io/badge/🌐%20Acessar%20LabMatch-111827?style=for-the-badge" alt="Acessar LabMatch">
</a>

<br><br>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">

<br>

<img src="https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white" alt="Radix UI">
<img src="https://img.shields.io/badge/Lucide-111827?style=for-the-badge&logo=lucide&logoColor=white" alt="Lucide">
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">

</div>

<br>

---

## 📌 Sobre o projeto

O **LabMatch** é um protótipo de uma plataforma para facilitar a utilização dos laboratórios em um ambiente acadêmico.

A ideia surgiu a partir de uma situação comum: o estudante precisa realizar uma atividade, mas nem sempre sabe **qual laboratório utilizar, quais recursos estão disponíveis ou se o espaço realmente atende às necessidades da atividade**.

Em vez de simplesmente apresentar uma lista de laboratórios, o LabMatch busca entender o que o estudante precisa fazer e apresentar opções mais compatíveis.

> **"Eu preciso de um laboratório, mas qual deles realmente serve para o que eu preciso fazer?"**

Essa é a pergunta central por trás da solução.

---

## 🎯 Objetivo

O principal objetivo do LabMatch é tornar a descoberta e a reserva de laboratórios uma experiência mais simples, rápida e clara.

A plataforma foi pensada para ajudar o estudante a:

- encontrar laboratórios disponíveis;
- verificar os recursos existentes;
- identificar espaços compatíveis com sua atividade;
- evitar reservas incompatíveis;
- consultar informações de acessibilidade;
- visualizar disponibilidade;
- acompanhar suas reservas;
- descobrir outros recursos e possibilidades dentro do ambiente acadêmico.

---

# 💡 O problema

Em um ambiente com diferentes laboratórios, equipamentos, horários e capacidades, encontrar o espaço adequado pode acabar sendo uma tarefa demorada.

O estudante pode precisar:

1. descobrir quais laboratórios existem;
2. verificar quais estão disponíveis;
3. procurar equipamentos;
4. conferir capacidade;
5. analisar horários;
6. verificar recursos de acessibilidade;
7. decidir qual espaço realmente atende à atividade;
8. realizar a reserva.

Quando essas informações estão espalhadas, aumenta a possibilidade de dúvidas e erros.

### Principais dificuldades identificadas

| Problema | Consequência |
| --- | --- |
| Muitos laboratórios disponíveis | Dificuldade para decidir |
| Informações espalhadas | Mais tempo procurando |
| Falta de compatibilidade clara | Escolhas inadequadas |
| Capacidade diferente entre laboratórios | Possibilidade de reserva incompatível |
| Recursos específicos | Necessidade de conferir informações manualmente |
| Acessibilidade pouco evidente | Dificuldade para encontrar espaços adequados |

---

# 🚀 A solução

O LabMatch propõe uma experiência baseada em **necessidade + contexto + compatibilidade**.

O estudante informa o que precisa e a plataforma apresenta laboratórios que podem atender àquela atividade.

### O fluxo principal

```text
O que preciso fazer?
        ↓
Quando vou utilizar?
        ↓
Quantas pessoas?
        ↓
Quais recursos preciso?
        ↓
Quais necessidades de acessibilidade?
        ↓
LabMatch analisa as opções
        ↓
Laboratórios compatíveis
        ↓
Escolha do laboratório
        ↓
Reserva
```

A ideia é reduzir a quantidade de decisões que o usuário precisa tomar sozinho.

---

# 🎯 O diferencial: Match

O conceito de **Match** é um dos principais elementos da solução.

Em vez de apresentar apenas:

> Laboratório A  
> Laboratório B  
> Laboratório C

o sistema procura responder:

> **Qual laboratório combina melhor com o que você pretende fazer?**

O usuário consegue visualizar uma indicação de compatibilidade e entender melhor por que determinado laboratório foi recomendado.

### O Match considera informações como:

- atividade;
- horário;
- disponibilidade;
- quantidade de pessoas;
- capacidade;
- equipamentos;
- recursos necessários;
- características do espaço;
- necessidades de acessibilidade.

---

# 🛡️ Prevenção de erros

Um dos pontos trabalhados no projeto foi a **prevenção de erros antes que eles aconteçam**.

Por exemplo:

> Se o estudante informa que precisa de um laboratório para **18 pessoas**, mas determinado espaço comporta apenas **10**, o sistema não deve incentivar uma reserva incompatível.

Em vez disso:

```text
❌ Laboratório incompatível

Capacidade disponível: 10 pessoas
Quantidade informada: 18 pessoas

→ Ver outras opções
```

A proposta é transformar o erro em uma oportunidade de orientação.

---

# ✨ Funcionalidades

<table>
<tr>
<td width="50%" valign="top">

### 🔎 Busca inteligente

Permite que o estudante encontre espaços a partir da atividade que deseja realizar.

</td>

<td width="50%" valign="top">

### 🎯 LabMatch

Apresenta opções de laboratórios de acordo com a compatibilidade com a necessidade informada.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🛡️ Prevenção de erros

Identifica incompatibilidades antes da confirmação de uma reserva.

</td>

<td width="50%" valign="top">

### 📅 Disponibilidade

Visualização dos horários e disponibilidade dos laboratórios.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧰 Equipamentos

Consulta dos recursos e equipamentos disponíveis em cada laboratório.

</td>

<td width="50%" valign="top">

### ♿ Acessibilidade

Informações e filtros relacionados às características de acessibilidade dos espaços.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📍 Localização

Ajuda o estudante a entender onde os laboratórios estão localizados dentro do ambiente acadêmico.

</td>

<td width="50%" valign="top">

### 📋 Reservas

Área para acompanhar reservas futuras e histórico de utilização.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 👥 Comunidade

Espaço pensado para interação entre estudantes, projetos e discussões.

</td>

<td width="50%" valign="top">

### 👤 Perfil

Centralização de informações, atividades, projetos e preferências do usuário.

</td>
</tr>
</table>

---

# 🖥️ Interface

A interface foi desenvolvida pensando em uma experiência **desktop-first**, com adaptação para diferentes tamanhos de tela.

A proposta visual utiliza uma identidade tecnológica, limpa e organizada, priorizando:

- hierarquia visual;
- contraste;
- legibilidade;
- espaçamento;
- consistência;
- feedback visual;
- navegação clara;
- componentes reutilizáveis.

### Direção visual

```text
Paleta principal
────────────────────────────────

Dark Navy       #0B1220
Blue            #2563EB
Light Blue      #60A5FA
White           #F8FAFC
Gray            #64748B
Dark Gray       #111827
```

A interface evita excesso de elementos decorativos e prioriza a informação necessária para a tomada de decisão.

---

## 📸 Telas do projeto

> Os espaços abaixo podem ser preenchidos com screenshots reais do protótipo.

### Login

```text
screenshots/login.png
```

### Dashboard

```text
screenshots/dashboard.png
```

### Busca e Match

```text
screenshots/match.png
```

### Reserva

```text
screenshots/reserva.png
```

### Perfil

```text
screenshots/perfil.png
```

> Para exibir as imagens no GitHub, basta colocar os arquivos dentro de uma pasta chamada `screenshots` e usar, por exemplo:
>
> `![Dashboard](./screenshots/dashboard.png)`

---

# 🧠 UX e IHC

O LabMatch foi desenvolvido como um projeto da disciplina de **Interação Humano-Computador (IHC)**, utilizando conceitos relacionados à experiência do usuário e usabilidade.

A proposta não foi apenas criar uma interface visualmente agradável, mas pensar em:

> **Como o usuário entende, utiliza e resolve sua necessidade dentro do sistema?**

---

# 👤 Perfil do usuário

O usuário principal considerado é o **estudante** que precisa utilizar um laboratório para realizar uma atividade acadêmica.

### Necessidades

- encontrar rapidamente um espaço;
- entender se o laboratório atende sua atividade;
- saber quando o espaço está disponível;
- conhecer os recursos disponíveis;
- evitar erros na reserva;
- receber informações claras;
- ter acesso a informações de acessibilidade.

### Contexto

O estudante pode estar entre aulas, com pouco tempo para pesquisar e tomar decisões.

Por isso, a interface deve reduzir etapas desnecessárias e apresentar informações relevantes no momento certo.

---

# 🧭 Jornada do usuário

A jornada foi organizada em cinco etapas:

```text
DESCOBRE
   ↓
ACESSA
   ↓
UTILIZA
   ↓
RESOLVE
   ↓
AVALIA
```

### 01 — DESCOBRE

O estudante percebe que precisa de um laboratório.

**Objetivo:** entender onde pode realizar sua atividade.

**Dificuldade:** não saber qual laboratório atende sua necessidade.

**Resposta do LabMatch:** apresentar uma busca orientada pela atividade.

---

### 02 — ACESSA

O estudante entra na plataforma.

**Objetivo:** iniciar rapidamente a busca.

**Dificuldade:** perder tempo navegando por muitas opções.

**Resposta do LabMatch:** acesso direto às principais ações.

---

### 03 — UTILIZA

O estudante informa sua necessidade.

**Objetivo:** encontrar espaços compatíveis.

**Dificuldade:** comparar manualmente diferentes laboratórios.

**Resposta do LabMatch:** apresentar opções com informações organizadas e Match.

---

### 04 — RESOLVE

O estudante escolhe o laboratório e realiza a reserva.

**Objetivo:** concluir a tarefa com segurança.

**Dificuldade:** escolher um espaço incompatível.

**Resposta do LabMatch:** prevenção de erros e feedback antes da confirmação.

---

### 05 — AVALIA

Após utilizar o sistema, o usuário pode avaliar a experiência.

**Objetivo:** melhorar continuamente a plataforma.

**Oportunidade:** utilizar feedback para identificar pontos de melhoria.

---

# 📐 Usabilidade

O projeto considera cinco dimensões clássicas de usabilidade:

| Dimensão | Aplicação no LabMatch |
| --- | --- |
| **Aprendizado** | Interface simples e ações reconhecíveis |
| **Eficiência** | Redução das etapas para encontrar um laboratório |
| **Memorização** | Organização consistente das telas |
| **Erros** | Prevenção de reservas incompatíveis |
| **Satisfação** | Feedback e sensação de controle durante a tarefa |

---

# 🔬 Heurísticas de Nielsen

Durante a concepção da solução, os princípios de usabilidade foram relacionados às decisões de interface.

| Heurística | Aplicação |
| --- | --- |
| **Visibilidade do status do sistema** | Informações de disponibilidade e feedback das ações |
| **Correspondência entre sistema e mundo real** | Termos e informações relacionados à rotina acadêmica |
| **Controle e liberdade do usuário** | Possibilidade de revisar informações antes de confirmar |
| **Consistência e padrões** | Componentes e comportamentos consistentes |
| **Prevenção de erros** | Bloqueio/orientação para situações incompatíveis |
| **Reconhecimento em vez de memorização** | Informações importantes apresentadas diretamente |
| **Flexibilidade e eficiência** | Busca e filtros para acelerar a localização |
| **Design minimalista** | Priorização das informações relevantes |
| **Ajudar a reconhecer e recuperar erros** | Mensagens claras quando algo não pode ser realizado |
| **Ajuda e documentação** | Informações contextuais para apoiar decisões |

---

# ♿ Acessibilidade

A acessibilidade foi considerada como parte da experiência, e não como um recurso separado.

### Alguns pontos considerados:

- contraste adequado;
- textos legíveis;
- botões com tamanho confortável;
- hierarquia visual;
- informações claras;
- estados visuais identificáveis;
- utilização de ícones acompanhados de contexto textual;
- filtros de acessibilidade;
- informações sobre características dos laboratórios;
- preocupação com navegação e interação.

### Exemplos de características consideradas

```text
♿ Entrada acessível
🪑 Espaço para cadeira de rodas
🧑‍💻 Mesa adaptada
🔊 Ambiente com menor ruído
💡 Iluminação
👁️ Sinalização visual
```

A ideia é permitir que o estudante consiga identificar previamente se determinado espaço atende às suas necessidades.

---

# 🧩 Arquitetura da experiência

O LabMatch foi pensado como mais do que uma tela de reserva.

A experiência pode ser dividida em diferentes áreas:

```text
                    LABMATCH
                       │
        ┌──────────────┼──────────────┐
        │              │              │
      Buscar         Explorar       Reservas
        │              │              │
      Match        Laboratórios    Próximas
        │           Equipamentos    Histórico
        │              │
        └──────────────┼──────────────┘
                       │
                 Comunidade
                       │
                    Perfil
```

Isso permite que a plataforma evolua futuramente para uma experiência mais completa dentro do ambiente acadêmico.

---

# 🛠️ Tecnologias utilizadas

<div align="center">

### Front-end

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">

### Interface

<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">
<img src="https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radixui&logoColor=white">
<img src="https://img.shields.io/badge/Lucide-111827?style=for-the-badge&logo=lucide&logoColor=white">

### Deploy

<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">

</div>

---

## ⚛️ React

O React foi utilizado para construir a interface através de componentes reutilizáveis.

Isso facilita a organização da aplicação e permite manter padrões visuais e comportamentais entre diferentes telas.

Exemplo de estrutura:

```tsx
function LabCard() {
  return (
    <div>
      <h3>Laboratório de Automação</h3>
      <p>Disponível hoje</p>
    </div>
  );
}
```

---

## 🔷 TypeScript

O TypeScript foi utilizado para adicionar tipagem ao projeto e facilitar a organização de dados e componentes.

Exemplo:

```ts
interface Laboratory {
  id: string;
  name: string;
  capacity: number;
  available: boolean;
}
```

---

## ⚡ Vite

O Vite é utilizado como ferramenta de desenvolvimento e build da aplicação.

```text
npm run dev
```

permite executar o projeto localmente durante o desenvolvimento.

---

## 🎨 Tailwind CSS

O Tailwind CSS foi utilizado para construir a identidade visual e adaptar a interface para diferentes tamanhos de tela.

A utilização de classes utilitárias também facilita a criação de componentes consistentes.

---

## 🧱 Radix UI

O Radix UI fornece componentes acessíveis e primitives para elementos de interface.

Ele ajuda a manter consistência e comportamento adequado em componentes como:

- dialogs;
- dropdowns;
- menus;
- tabs;
- tooltips;
- controles de interface.

---

## ✨ Lucide Icons

O projeto utiliza ícones da biblioteca Lucide para manter uma linguagem visual consistente.

A utilização de ícones ajuda na compreensão rápida das ações sem depender exclusivamente de elementos decorativos.

---

# 📁 Estrutura do projeto

A estrutura principal está organizada da seguinte forma:

```text
labmatch/
│
├── public/
│
├── src/
│   ├── components/
│   ├── hooks/
│   ├── lib/
│   ├── pages/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
│
├── .gitignore
├── components.json
├── index.html
├── package.json
├── README.md
├── tsconfig.json
├── tsconfig.node.json
├── vercel.json
└── vite.config.ts
```

A organização busca separar componentes, páginas e recursos da aplicação, facilitando futuras alterações.

---

# 💻 Como executar localmente

## Pré-requisitos

Antes de começar, é necessário ter instalado:

- Node.js
- npm
- Git

Para conferir:

```bash
node -v
npm -v
git --version
```

---

## 1. Clonar o repositório

```bash
git clone https://github.com/romanolc/labmatch.git
```

Entrar na pasta:

```bash
cd labmatch
```

---

## 2. Instalar as dependências

```bash
npm install
```

---

## 3. Executar o projeto

```bash
npm run dev
```

O Vite irá disponibilizar o projeto localmente, normalmente em:

```text
http://localhost:5173/
```

---

# 🔐 Acesso para demonstração

Para testar a aplicação:

| Campo | Valor |
| --- | --- |
| **RA** | `20260001` |
| **Senha** | `123456` |

> Essas credenciais são destinadas exclusivamente à demonstração do protótipo.

---

# 📜 Scripts disponíveis

| Comando | Função |
| --- | --- |
| `npm run dev` | Executa o ambiente de desenvolvimento |
| `npm run build` | Gera a versão de produção |
| `npm run preview` | Visualiza o build localmente |
| `npm run check` | Executa verificações do projeto |
| `npm run format` | Formata os arquivos |

---

# 🚀 Build de produção

Para gerar a versão de produção:

```bash
npm run build
```

Depois:

```bash
npm run preview
```

---

# 🌐 Deploy

O projeto está publicado na Vercel.

<div align="center">

<a href="https://labmatch-eosin.vercel.app">

<img src="https://img.shields.io/badge/ABRIR%20LABMATCH-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Abrir LabMatch">

</a>

<br><br>

**https://labmatch-eosin.vercel.app**

</div>

O projeto utiliza uma configuração de SPA para permitir a navegação entre as rotas da aplicação.

Arquivo utilizado:

```text
vercel.json
```

---

# 🔄 Fluxo de atualização

Para atualizar o projeto depois de realizar alterações localmente:

```bash
git status
```

Adicionar os arquivos:

```bash
git add .
```

Criar o commit:

```bash
git commit -m "feat: atualiza LabMatch"
```

Enviar para o GitHub:

```bash
git push origin main
```

---

# 🎓 Contexto acadêmico

<div align="center">

### SENAI CIMATEC

**Desenvolvimento de Sistemas**

**Turma:** 96213

**Disciplina:** Interação Humano-Computador (IHC)

**Professor:** Marcos Santos Leite

</div>

---

# 👥 Equipe

| Integrante |
| --- |
| **Brahyan Dias Ramos** |
| **Ícaro Ricardo Rodrigues Santos** |
| **João Guilherme Moreira de Santana** |
| **Lucca Romano** |

---

# 📚 O que foi aplicado no projeto

Durante o desenvolvimento do LabMatch foram trabalhados conceitos relacionados a:

- Interação Humano-Computador;
- UX Design;
- UI Design;
- usabilidade;
- acessibilidade;
- jornada do usuário;
- perfil do usuário;
- necessidades e contexto;
- heurísticas de Nielsen;
- prevenção de erros;
- feedback;
- prototipação;
- arquitetura de informação;
- design responsivo;
- componentes reutilizáveis.

---

# 🔎 Relação entre problema, decisão e benefício

Uma das preocupações do projeto foi não tratar UX apenas como estética.

| Problema | Decisão de design | Benefício |
| --- | --- | --- |
| Muitos laboratórios | Busca inteligente | Menos tempo procurando |
| Dificuldade para escolher | Match | Comparação mais simples |
| Reserva incompatível | Prevenção de erros | Menos falhas |
| Informações espalhadas | Organização por contexto | Maior clareza |
| Necessidades diferentes | Filtros de acessibilidade | Maior inclusão |
| Dúvidas durante a tarefa | Feedback | Maior segurança |

---

# 🧪 Prototipação

O protótipo foi desenvolvido com foco na simulação de uma experiência real de uso.

A proposta foi testar principalmente o fluxo:

```text
Necessidade
    ↓
Busca
    ↓
Compatibilidade
    ↓
Escolha
    ↓
Reserva
```

Esse fluxo permite observar se o estudante consegue chegar ao resultado sem precisar conhecer previamente todos os laboratórios disponíveis.

---

# 📈 Possíveis evoluções

O LabMatch foi desenvolvido como uma base que pode continuar evoluindo.

Algumas possibilidades futuras:

- integração com dados reais dos laboratórios;
- disponibilidade em tempo real;
- integração com calendário acadêmico;
- notificações;
- sistema de confirmação de presença;
- QR Code para check-in;
- lista de espera;
- avaliações dos laboratórios;
- recomendações mais personalizadas;
- integração com sistemas institucionais;
- painel administrativo;
- dados reais de equipamentos;
- métricas de utilização;
- melhorias baseadas em testes com usuários.

---

# 🧠 Por que "LabMatch"?

O nome representa diretamente a proposta do projeto:

**Lab + Match**

> Encontrar o laboratório que melhor combina com a necessidade do estudante.

O conceito também permite que a plataforma evolua para diferentes tipos de atividades e perfis de usuários.

---

# 🗺️ Visão futura

A ideia do LabMatch não termina na reserva.

A longo prazo, a plataforma pode se tornar uma espécie de **ponto central para descoberta e utilização dos espaços acadêmicos**, conectando:

```text
Estudantes
     │
     ├── Laboratórios
     │
     ├── Equipamentos
     │
     ├── Reservas
     │
     ├── Projetos
     │
     ├── Comunidade
     │
     └── Oportunidades
```

Assim, a reserva deixa de ser uma tarefa isolada e passa a fazer parte de uma experiência acadêmica mais completa.

---

# 📌 Status do projeto

<div align="center">

![Status](https://img.shields.io/badge/STATUS-PROTÓTIPO-2563EB?style=for-the-badge)

![Version](https://img.shields.io/badge/VERSION-1.0-111827?style=for-the-badge)

</div>

O projeto encontra-se em estágio de protótipo acadêmico, com foco na validação da experiência, aplicação dos conceitos de IHC e demonstração da solução.

---

# 🔗 Links

| Recurso | Acesso |
| --- | --- |
| 🌐 Projeto publicado | [LabMatch](https://labmatch-eosin.vercel.app) |
| 💻 Repositório | [GitHub](https://github.com/romanolc/labmatch) |

---

<div align="center">

# 🔷 LabMatch

### Encontra o laboratório que combina com sua atividade.

<br>

**Projeto acadêmico desenvolvido no SENAI CIMATEC**

<br>

<img src="https://img.shields.io/badge/Feito%20com-React%20%2B%20TypeScript-3178C6?style=for-the-badge&logo=react&logoColor=white">

<br><br>

⭐ Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório.

</div>
