# 🎵 Escola Modelar Cambaúba - Músicas da Copa

<p align="center">
  <img src="https://img.shields.io/badge/Status-Online-success?style=for-the-badge" alt="Status Online" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
</p>

---

## 📖 Sobre o Projeto

Aplicação web interativa criada para celebrar e divulgar os trabalhos musicais e cordéis dos alunos do 6º ano (**Turmas 601 e 602**) da **Escola Modelar Cambaúba**, no âmbito do projeto interdisciplinar da **Copa do Mundo**.

O site reúne **23 produções exclusivas dos estudantes**, organizadas por turmas, em um player de áudio responsivo com design moderno.

---

## 🌐 Acesso Online

- **Deploy na Vercel:** [https://copa-cambauba-.vercel.app](https://copa-cambauba-.vercel.app)
- **Repositório no GitHub:** [Lucas-dev100/copa-cambauba-](https://github.com/Lucas-dev100/copa-cambauba-)

---

## ✨ Funcionalidades Principais

- 🎧 **Player de Áudio Dinâmico:**
  - Controles completos (Play, Pause, Próxima faixa, Faixa anterior).
  - Barra de progresso interativa com busca em tempo real (*seek bar*).
  - Marcadores de tempo decorrido e duração total da música.
  - Controle de volume com slider deslizante.
  - Avanço automático para a próxima faixa ao término da música.

- 📋 **Playlist Categorizada por Turma:**
  - Divisão explícita entre **Turma 601** e **Turma 602**.
  - Destaque visual da música atualmente em reprodução.
  - Reprodução instantânea ao clicar em qualquer item da lista.

- 📱 **Design Moderno e Responsivo:**
  - Interface escura (*Dark Mode*) com paleta refinada (*Slate* e detalhes em *Âmbar*).
  - Elementos em *Glassmorphism* e sombras suaves.
  - 100% responsivo para celulares, tablets e computadores.

---

## 🎼 Lista de Músicas e Créditos dos Alunos (23 Faixas)

### 🔹 Turma 601 (11 faixas)
| # | Música | Autores / Alunos |
|:---:|---|---|
| **01** | Brasil na Copa | Davi e Gabriel |
| **02** | Produção Especial | Yasmin e Ingrid |
| **03** | Cordel Alternativo | Jojo e Duda |
| **04** | Futebol e Emoção | Khadija |
| **05** | Espírito Esportivo | Ludmila |
| **06** | Paixão Nacional | Marcelo e Maria Luiza C. |
| **07** | Canção da Torcida | Maria Luiza e Manuela |
| **08** | Copa Especial | Mariana Grillo e Catharina |
| **09** | Hino da Copa | Noah |
| **10** | Rap da Copa | Daiha e Henrique |
| **11** | Samba do Brasil | Samuel e Eduardo |

### 🔹 Turma 602 (12 faixas)
| # | Música | Autores / Alunos |
|:---:|---|---|
| **12** | Apresentação Turma 602 | Introdução Geral |
| **13** | Música Alunos | Ana Flor e Mariana |
| **14** | Futebol e Torcida | Ciça e Ágatha |
| **15** | Cordel Vera Redação | Daniel e Tarsila |
| **16** | Canção da Copa | Giovana e Maria Fernanda |
| **17** | Paixão pelo Esporte | João Antônio e Vitor Fadel |
| **18** | Apresentação Especial | Lara e Julia |
| **19** | Futebol Maneiro | Miguel Almeida e Guilherme Portes |
| **20** | Hino e Emoção | Miguel Cardeal e Gabriel Cardoso |
| **21** | Cordel Redação | Vera, Vinícius, Helena e Lorenzo |
| **22** | Música Alunos | Nina e Fernanda |
| **23** | Trabalho de Cordel | Vitor Lima e João Pedro Neves |

---

## 🛠️ Tecnologias e Recursos

- **HTML5 Semântico** - Arquitetura e acessibilidade da página.
- **JavaScript (Vanilla ES6+)** - Lógica e controle do reprodutor de áudio via API `HTMLAudioElement`.
- **Tailwind CSS** - Framework utilitário para estilização e responsividade.
- **Font Awesome 6** - Ícones de mídia e navegação.
- **Git & GitHub** - Versionamento de código-fonte.
- **Vercel** - Hospedagem em nuvem com *Continuous Deployment* (CI/CD) automático.

---

## 📁 Estrutura de Arquivos

```plaintext
copa-cambauba/
├── index.html            # Aplicação web principal (HTML + JS + Tailwind)
├── README.md             # Documentação do projeto
├── .gitignore            # Arquivos ignorados pelo Git
└── *.mp3                 # Faixas de áudio das turmas 601 e 602
```

---

## 💻 Como Rodar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Lucas-dev100/copa-cambauba-.git
   cd copa-cambauba-
   ```

2. **Abra o projeto:**
   - Dê um duplo clique no arquivo `index.html` para abrir diretamente no navegador, ou
   - Use um servidor local simples, como a extensão **Live Server** do VS Code.

---

## 🔄 Deploy Contínuo (Vercel)

Qualquer alteração enviada para o branch principal (`main`) no GitHub dispara automaticamente um novo build na **Vercel**, mantendo a versão de produção sempre sincronizada e disponível 24/7.
