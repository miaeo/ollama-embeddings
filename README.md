# ollama-embeddings

Projeto simples de geração e manipulação de **embeddings de texto** utilizando o modelo `mxbai-embed-large` com **Ollama** em ambiente local, para projeto de Tópicos Avançados em Sistemas para Internet I.

---

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- [Python 3.10+](https://www.python.org/)
- [Ollama](https://ollama.com/) instalado e configurado localmente
- Git

---

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/ollama-embeddings-projeto.git
cd ollama-embeddings-projeto
```

### 2. (Opcional) Crie um ambiente virtual

```bash
python -m venv venv
```
No Powershell, ative seu ambiente virtual

```bash
.\venv\Scripts\Activate.ps1
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

## Execução

### 1. Inicie o Ollama

Certifique-se de que o Ollama esteja rodando antes de executar o script!

```bash
ollama run llama2
```

### 2. Em outro terminal, execute o script

```bash
python embeddings_ollama.py
```

O script exibirá:

- O tamanho do vetor de embedding gerado
- Os primeiros valores do vetor da query
- A frase mais similar com base na similaridade de embeddings
