# azure-tradutor-de-artigos-tecnicos
Desafio de projeto DIO

# 🌐 Azure AI Translator - Lab AI 102 📝

## 📒 Descrição
Este projeto utiliza o serviço Azure Cognitive Services Translator para traduzir textos e documentos. A aplicação automatiza a tradução para português (ou qualquer idioma desejado), facilitando a adaptação de conteúdos em diferentes idiomas. Esse processo é essencial para empresas que lidam com documentos multilíngues e buscam otimizar a comunicação.

## 🧐 Processo de Criação
O projeto foi desenvolvido com uma interface em Python para chamar a API de tradução da Microsoft Azure. Ele utiliza a biblioteca `requests` para fazer requisições à API e `python-docx` para manipular documentos `.docx`.

### Etapas:
1. **Instalação de Bibliotecas**: Instalação de `requests` e `python-docx` para acessar a API de tradução e manipular documentos.
2. **Configuração da API**: Definição de `subscription_key`, `endpoint` e `location`, específicos para o serviço de tradução da Azure.
3. **Função de Tradução**: Implementação da função `translator_text` para traduzir texto diretamente.
4. **Função de Tradução de Documentos**: Implementação da função `translate_document` para realizar traduções em documentos `.docx`, salvando o resultado em um novo arquivo.
5. **Execução e Teste**: Testes e ajustes das funções para garantir traduções precisas e manipulação correta dos documentos.

## 🚀 Resultados
O projeto entrega traduções rápidas e precisas de textos e documentos. Utilizando o Azure Translator, é possível processar uma grande quantidade de texto com eficiência e adaptá-lo a diferentes idiomas, permitindo maior acessibilidade e alcance.

### Tradução de Texto Simples
A função `translator_text` permite traduzir frases ou parágrafos de forma prática, útil para conteúdos curtos ou mensagens instantâneas.

### Tradução de Documentos .docx
A função `translate_document` processa arquivos `.docx` completos, traduzindo cada parágrafo e salvando o resultado em um novo arquivo, ideal para traduções em massa de relatórios ou documentos extensos.

## 💭 Reflexão
Este projeto ilustra o poder da API de tradução do Azure na automação de tarefas de tradução. Com a capacidade de traduzir grandes volumes de texto de forma rápida.
Importante considerar que com o serviço de tradução é possível traduzir até 2M de caracteres Free, e acima disso o próximo 1M é ~R$54. Já o serviço OpenAi no Azure, é possível traduzir igualmente seus arquivos, com valor 10x menor ~R$5 a cada 1M tokens usando o GPT 4o-mini.
