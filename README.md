# OCI Generative AI Assistant

Assistente inteligente desenvolvido com os serviços de Inteligência Artificial Generativa da Oracle Cloud Infrastructure (OCI), utilizando modelos de linguagem avançados para processamento de linguagem natural, geração de conteúdo e automação de tarefas.

## Visão Geral

Este projeto tem como objetivo demonstrar a utilização dos recursos de IA Generativa da Oracle Cloud Infrastructure (OCI) na construção de um assistente inteligente capaz de compreender solicitações em linguagem natural, gerar respostas contextualizadas e auxiliar usuários em diferentes fluxos de trabalho.

## Funcionalidades

- Integração com OCI Generative AI
- Processamento de linguagem natural (NLP)
- Geração de respostas contextualizadas
- Suporte a prompts personalizados
- Arquitetura escalável em nuvem
- Fácil integração com aplicações web e APIs
- Estrutura preparada para evolução e treinamento de casos de uso específicos

## Tecnologias Utilizadas

- Python
- Oracle Cloud Infrastructure (OCI)
- OCI Generative AI
- OCI SDK
- REST APIs
- Git e GitHub

## Pré-requisitos

Antes de iniciar, certifique-se de possuir:

- Python 3.10 ou superior
- Conta Oracle Cloud Infrastructure (OCI)
- Chaves e credenciais configuradas para acesso à OCI
- Git instalado

## Instalação

Acesse a pasta do projeto:

```bash
cd oci_genai_4585
```

Crie e ative um ambiente virtual:

```bash
python -m venv venv

# Linux/Mac
source venv/bin/activate

# Windows
venv\Scripts\activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

## Configuração

Configure suas credenciais OCI no arquivo padrão:

```text
~/.oci/config
```

Ou defina as variáveis de ambiente necessárias:

```bash
OCI_PROFILE=DEFAULT
OCI_REGION=<sua-regiao>
OCI_COMPARTMENT_ID=<compartment_id>
```

## Execução

Execute a aplicação:

```bash
python main.py
```

Ou execute o módulo principal:

```bash
python -m src.main
```

## Exemplo de Uso

Entrada:

```text
Explique o que é IA Generativa.
```

Saída:

```text
IA Generativa é uma categoria de Inteligência Artificial capaz de criar novos conteúdos, como textos, imagens, códigos e áudios, a partir de dados e instruções fornecidas pelos usuários.
```

Desenvolvido com Oracle Cloud Infrastructure Generative AI 
