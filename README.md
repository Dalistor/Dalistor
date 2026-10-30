<div align="center">

# Diego Cabral

### Engenheiro de Software · Arquitetura de Sistemas · Desenvolvimento com IA

*Do problema à validação — com a IA na implementação e o humano na intenção.*

![Arquitetura](https://img.shields.io/badge/Arquitetura-de_Sistemas-1f6feb?style=for-the-badge)
![IA](https://img.shields.io/badge/Desenvolvimento-com_IA-8957e5?style=for-the-badge)
![Distribuídos](https://img.shields.io/badge/Sistemas-Distribuídos-238636?style=for-the-badge)
![WorldSkills](https://img.shields.io/badge/WorldSkills-Robótica_Móvel-f78166?style=for-the-badge)

[📫 Email](mailto:diego.sil.cabral@gmail.com) · [🧭 Centaur-Driven](https://github.com/Dalistor/Centaur-Driven)

</div>

---

## 👋 Sobre mim

Desenvolvo produtos de software, sistemas distribuídos, automações e ferramentas voltadas para o desenvolvimento assistido por Inteligência Artificial.

Com o avanço das ferramentas de IA, meu trabalho se concentra cada vez menos em escrever cada linha de código manualmente e mais em:

> **arquitetura · requisitos · contratos · fluxos · integração entre sistemas · validação das implementações geradas**

---

## 🚀 Projetos em destaque

### 🧭 [Centaur-Driven](https://github.com/Dalistor/Centaur-Driven)

> Metodologia e conjunto de ferramentas para desenvolvimento de software com agentes de IA.

O humano continua responsável por **intenção, arquitetura, regras e limites do sistema**, enquanto agentes de IA assumem partes cada vez maiores da implementação.

| Conceito | Descrição |
|---|---|
| 📜 **Contratos e especificações** | Contratos versionados e especificações estruturadas |
| ✅ **Requisitos** | Funcionais, não funcionais e casos de uso |
| 🧪 **TDD** | Testes guiando a implementação |
| 🔗 **Rastreabilidade** | Ligação entre regras, código, testes e evidências de validação |
| 🧠 **Memória e contexto** | Contexto persistente para agentes |
| 🤖 **Multiagentes** | Vários agentes trabalhando em conjunto |
| 🗺️ **Visualização** | Arquitetura e fluxos do sistema |
| 💻 **VS Code** | Integração direta com o editor |

A ideia é explorar como o desenvolvimento funciona quando **ler e escrever manualmente todo o código deixa de ser a principal interface de desenvolvimento**.

---

### 🎬 [video-engine](https://github.com/Dalistor/video-engine)

> Motor universal de animação em vídeo, operado por um agente de IA (Claude).

Explicadores, vídeos curtos para redes sociais, motion graphics, cenas 3D e apresentações animadas: qualquer coisa que se descreva como **uma página que desenha o instante `t`**. O Claude escreve o roteiro, gera as vozes via MCP do ElevenLabs e roda as ferramentas do motor; no fim, sobra o `.mp4` final.

```text
Claude + MCP ElevenLabs → projects/<id>/ → output/<slug>_final.mp4 → cleanup descarta vozes e intermediários
```

| Conceito | Descrição |
|---|---|
| 🧮 **Quadros determinísticos** | Cada quadro é uma função pura de `t` (Canvas 2D ou Three.js): prévia, trecho e render final geram a mesma imagem |
| 🎞️ **Pipeline** | Playwright posiciona a página no instante, captura o canvas e o ffmpeg codifica |
| 🧊 **3D e bibliotecas** | Three.js, GSAP, Lottie, MathJax, física com `simulate()` |
| 🔊 **Som gerado pela página** | Música, motor, sirene com efeito Doppler: imagem e som saem das mesmas funções, então batem no mesmo quadro |
| 🎵 **Tempo por voz, música ou fixo** | Cortes que caem nas batidas, legendas sincronizadas por palavra |
| 🤖 **Agente como operador** | Ferramentas com saída objetiva e códigos de saída claros para o agente ler e corrigir |
| 🔍 **Controle de qualidade** | Lint, teste de determinismo, detector de saltos 3D, retenção, `verify.py` e inspetor visual com notas de direção |
| 📐 **Múltiplos formatos** | Vertical, horizontal, quadrado, 4K ou resolução livre |

Node · Python · Playwright · ffmpeg · Three.js · ElevenLabs

---

### 🛠️ Workerrs

> Plataforma que conecta clientes a profissionais de serviços por meio de uma experiência conversacional.

Usa automação e IA para entender a necessidade do usuário, localizar profissionais compatíveis e facilitar o contato via WhatsApp.

- 🤖 Agentes de IA para atendimento conversacional
- 💬 Integração com WhatsApp
- 🔎 Busca e recomendação de profissionais
- 📍 Filtragem por localização
- 👤 Perfis com imagens e descrições dos prestadores
- 💳 Assinaturas para prestadores
- 📣 Divulgação segmentada por região
- ⚙️ Automação do fluxo cliente ↔ profissional

O Workerrs também é um experimento de **produto, monetização e aquisição de usuários**, indo além da implementação técnica.

---

## 🧠 Áreas de interesse

| | Área | Foco |
|---|---|---|
| 🏗️ | **Arquitetura de Sistemas** | Responsabilidades, módulos, serviços, bancos de dados, comunicação e fluxos de informação |
| 🤖 | **Engenharia de Software com IA** | Agentes para implementação, refatoração, testes e análise, com requisitos e decisões sob controle humano |
| 🌐 | **Sistemas Distribuídos** | APIs, tempo real, aplicações locais e remotas, sincronização e integração de serviços |
| 📦 | **Engenharia de Produto** | Da ideia ao sistema completo: arquitetura, UX, infraestrutura, manutenção e evolução |
| 🔧 | **Automação e Ferramentas** | Reduzir trabalho repetitivo e melhorar a construção e manutenção de software |

---

## 🏆 WorldSkills

Ex-competidor nacional da modalidade **#23 — Robótica Móvel**.

A robótica moldou minha visão de software: não como código isolado, mas como um conjunto de componentes que precisam se comunicar e trabalhar juntos.

---

## 🧩 Como trabalho

Não me defino por linguagens ou frameworks. Linguagens são ferramentas, e a escolha depende do problema.

```text
Problema → Arquitetura → Requisitos → Contratos → Implementação com IA → Testes → Validação
```

Meu foco está em entender:

- 🎯 o que o sistema precisa fazer;
- 🔗 como suas partes devem se relacionar;
- 📌 onde cada responsabilidade deve ficar;
- 🌊 como os dados devem fluir;
- ✔️ como validar o comportamento produzido pela IA.

---

## 📂 Outros projetos

Meu GitHub também reúne projetos de anos de experimentação com automação, APIs, aplicações desktop, inteligência artificial e robótica. Eles mostram minha evolução como desenvolvedor e minhas diferentes formas de construir sistemas.

---

<div align="center">

## 📫 Contato

**[diego.sil.cabral@gmail.com](mailto:diego.sil.cabral@gmail.com)**

</div>
