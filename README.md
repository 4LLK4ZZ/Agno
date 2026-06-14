# 🤖 Agno Multi-Agent Studies

Este repositório foi criado para documentar e organizar meus estudos práticos sobre o desenvolvimento de sistemas **Multi-Agentes** utilizando o framework **Agno** (anteriormente conhecido como Phidata).

O objetivo é evoluir desde conceitos fundamentais de agentes simples até arquiteturas mais avançadas, integrando ferramentas externas, busca de informações, instruções customizadas e mecanismos de tomada de decisão complexos.

---

## 📚 Objetivos de Aprendizagem

* Compreender os fundamentos do framework Agno.
* Desenvolver agentes autônomos com acesso a ferramentas externas.
* Explorar técnicas de engenharia de prompt e definição de personas.
* Implementar agentes com capacidade de raciocínio estruturado.
* Construir aplicações práticas utilizando múltiplos agentes colaborativos.
* Integrar LLMs e APIs externas para resolução de problemas reais.

---

## 📂 Estrutura do Projeto

A organização dos arquivos segue uma trilha de aprendizado progressiva:

| Arquivo                   | Descrição                                                                                                                               |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| `1-agent_basic.py`        | Implementação inicial de um agente simples para compreender o ciclo de vida básico e as chamadas do framework.                          |
| `2-agent_tool.py`         | Integração do agente com ferramentas externas (*Tools*), permitindo executar ações e consultar dados dinâmicos.                         |
| `3-agent_youtube.py`      | Agente configurado para interagir e processar conteúdos provenientes do YouTube.                                                        |
| `3-youtube.py`            | Versão alternativa para experimentos com busca e leitura de conteúdo em vídeos.                                                         |
| `4-agent_instructions.py` | Estudo de engenharia de prompts e definição de instruções estruturadas para controle da persona do agente.                              |
| `5-agent_reasoning.py`    | Implementação de agentes com capacidade de raciocínio avançado antes da execução de ações.                                              |
| `app_finance_agent.py`    | Aplicação prática voltada ao mercado financeiro, utilizando múltiplos agentes para análise de ações, notícias e indicadores econômicos. |
| `requirements.txt`        | Lista de dependências necessárias para execução do projeto.                                                                             |

---

## 🛠️ Tecnologias Utilizadas

* Python 3.10+
* Agno Framework
* OpenAI
* Google Gemini
* Ollama
* APIs de terceiros
* Ambiente virtual (`venv`)

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
cd NOME_DO_REPOSITORIO
```

### 2. Crie e ative um ambiente virtual

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### Linux/macOS

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```env
OPENAI_API_KEY=sua_chave_aqui
GEMINI_API_KEY=sua_chave_aqui
```

Adicione outras chaves de API conforme necessário para os exemplos estudados.

### 5. Execute um dos exemplos

```bash
python 1-agent_basic.py
```

---

## 🧠 Conceitos Explorados

### Autonomia

Configuração de ferramentas para permitir que a LLM decida quando e como buscar informações externas em tempo real.

### Especialização

Criação de agentes especializados com personas, regras de negócio e comportamentos definidos por instruções estruturadas.

### Raciocínio

Implementação de estratégias de raciocínio para melhorar a qualidade das decisões tomadas pelos agentes.

### Orquestração

Coordenação entre múltiplos agentes e diferentes fontes de dados para geração de respostas e relatórios consolidados.

---

## 📈 Projeto em Destaque

### Finance Agent

O arquivo `app_finance_agent.py` representa uma aplicação prática que combina múltiplos agentes especializados para:

* Análise de ações e ativos financeiros;
* Consulta de notícias econômicas;
* Avaliação de indicadores de mercado;
* Geração automatizada de relatórios consolidados.

---

## 📖 Referências

* Documentação oficial do Agno
* OpenAI API
* Google Gemini API
* Ollama

---

## 🤝 Contribuições

Este projeto tem caráter educacional e experimental. Sugestões, melhorias e novas ideias são sempre bem-vindas.

---

### 👨‍💻 Autor

**4LLK4ZZ**

Estudos e experimentos com agentes inteligentes, LLMs e arquiteturas Multi-Agent.
