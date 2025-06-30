# AzureCognitiveSearchDIO

# Guia de Instalação e Uso

Este tutorial fornece um guia passo a passo simples para instalar e começar a usar o Azure Language Studio, um serviço da Microsoft para processamento de linguagem natural.

## Pré-requisitos

- Conta ativa no [Microsoft Azure](https://azure.microsoft.com/)
- Assinatura do Azure (pode usar a camada gratuita)
- Navegador moderno (Chrome, Edge, Firefox ou Safari)

## Passo 1: Criar o Recurso no Azure

1. Acesse o [Portal do Azure](https://portal.azure.com/)
2. No campo de busca, digite "Language Service" e selecione a opção
3. Clique em "Criar"
4. Preencha os detalhes:
   - **Assinatura**: Selecione sua assinatura
   - **Grupo de recursos**: Crie um novo ou selecione existente
   - **Nome**: Dê um nome ao seu serviço (ex: "MeuLanguageService")
   - **Localização**: Selecione a região mais próxima
   - **Tipo de preço**: Selecione "Free F0" para teste
5. Clique em "Revisar + criar" e depois em "Criar"

## Passo 2: Acessar o Language Studio

1. Após a criação do recurso, acesse [Language Studio](https://language.azure.com/)
2. Faça login com sua conta Azure
3. Selecione o recurso que você acabou de criar

## Funcionalidades Básicas

### Análise de Texto
1. No menu esquerdo, selecione "Análise de texto"
2. Digite ou cole um texto na caixa de entrada
3. Selecione as operações desejadas:
   - Extração de frases-chave
   - Reconhecimento de entidades
   - Análise de sentimentos
4. Clique em "Executar" para ver os resultados

### Conversa Personalizada
1. Selecione "Conversa personalizada" no menu
2. Clique em "Criar um projeto"
3. Defina um nome e descrição
4. Importe dados de treinamento ou comece do zero
5. Treine e publique seu modelo de conversação

## Usando a API

Para integrar em seus aplicativos, você pode usar as chaves de API:

1. No Portal do Azure, navegue até seu recurso de Language Service
2. Em "Chaves e Endpoint", copie:
   - Chave de API
   - Endpoint
3. Use esses dados para autenticar suas chamadas à API

## Limpeza (Opcional)

Para evitar cobranças indesejadas:
1. No Portal do Azure, navegue até seu Grupo de Recursos
2. Selecione o recurso do Language Service
3. Clique em "Excluir"

## Recursos Adicionais

- [Documentação Oficial](https://docs.microsoft.com/azure/cognitive-services/language-service/)
- [Exemplos de Código](https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/textanalytics/azure-ai-textanalytics/samples)
