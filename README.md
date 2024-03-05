# DIO--Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI

Bem-vindo à exploração da IA generativa com o Microsoft Copilot! Neste exercício, vou orientá-lo através dos passos para aproveitar ao máximo essa poderosa ferramenta.

## Login no Microsoft Copilot

1. Acesse [copilot.microsoft.com](https://copilot.microsoft.com) e faça login com sua conta pessoal da Microsoft.

2. Explore a Janela "Pergunte-me Qualquer Coisa" na parte inferior da tela. O Copilot usa IA generativa para aprimorar os resultados de pesquisa, gerando respostas com base em modelagem de linguagem natural e informações da web.

## Usando Prompts para Gerar Respostas

1. **Perguntas sobre Viagens:**
   - Digite um prompt como: "What are 3 pros and cons of traveling in the winter?". Observe como o Copilot gera respostas originais, baseando-se em respostas pesquisadas e fornecendo links para fontes.

2. **Explorando Mais com Prompts:**
   - Experimente "Find me 3 more pros" para obter motivos adicionais para viajar no inverno, construindo sobre a resposta anterior.

3. **Buscando Lugares com Menos Multidão:**
   - Teste "Where are 3 places I can go to find fewer crowds?". Observe a capacidade do Copilot de entender e aplicar informações do chat anterior.

## Observações Importantes

- O botão "Novo Tópico" é útil para limpar o histórico de conversas, garantindo respostas não baseadas em tópicos anteriores.

## Explorando Geração de Imagens

1. **Criando uma Imagem:**
   - Experimente "Create an image of an elephant eating a hamburger". Observe a mensagem "Powered by DALL-E" indicando que a resposta é gerada usando modelos de linguagem.

## Experimentando a Geração e Tradução de Código

1. **Usando Python e Traduzindo para C#:**
   - Digite prompts como "Use Python to create a list" e em seguida "Translate that into C#". Observe como o Copilot entende o contexto da conversa.


# Explorando o Azure OpenAI

Bem-vindo à exploração do Azure OpenAI, onde mergulharemos nos modelos generativos de IA fornecidos pela OpenAI, agora disponíveis na plataforma Azure. Vamos criar soluções de IA poderosas aproveitando a segurança, escalabilidade e integração de serviços oferecidos pela plataforma de nuvem Azure.

## Antes de Começar

1. Certifique-se de ter uma assinatura do Azure aprovada para acessar o Azure OpenAI. Caso ainda não tenha, inscreva-se para uma [assinatura gratuita do Azure](https://azure.microsoft.com/free).

2. Solicite acesso ao serviço Azure OpenAI em [aka.ms/oaiapply](https://aka.ms/oaiapply).

## Provisionando um Recurso Azure OpenAI

1. Acesse o [portal do Azure](https://portal.azure.com/).

2. Crie um recurso Azure OpenAI com as seguintes configurações:
   - **Assinatura:** Sua assinatura do Azure aprovada.
   - **Grupo de Recursos:** Escolha ou crie um grupo de recursos.
   - **Região:** Selecione uma região disponível.
   - **Nome:** Um nome exclusivo de sua escolha.
   - **Nível de Preços:** Padrão S0

3. Aguarde a conclusão da implantação e acesse o recurso Azure OpenAI no portal do Azure.

## Explorando o Azure OpenAI Studio

1. No painel de Visão Geral do recurso Azure OpenAI, clique em "Explorar" para abrir o Azure OpenAI Studio em um novo navegador ou acesse diretamente [Azure OpenAI Studio](https://studio.openai.azure.com/).

2. Familiarize-se com as páginas disponíveis, incluindo um playground para experimentar modelos.


## Implantando um Modelo de Geração de Linguagem

1. Na página "Modelos", escolha um modelo gpt-35-turbo com status "Implantável" e clique em "Implantar".



2. Crie uma nova implantação com configurações adequadas.

## Usando o Playground do Chat

1. No Azure OpenAI Studio, vá para o "Playground do Chat" no painel esquerdo.

2. Configure a implantação do modelo e teste com prompts, interagindo em uma interface de chat.

## Geração de Imagens com o Playground DALL-E

1. Acesse o "Playground DALL-E" no painel esquerdo.

2. Experimente gerar imagens inserindo prompts, como "A robot eating spaghetti". Visualize os resultados.

3. Solicite acesso à funcionalidade DALL-E para explorar modelos de geração de imagens.

## Limpeza

Quando terminar, lembre-se de excluir a implantação ou o recurso completo no [Portal do Azure](https://portal.azure.com/).




# Explorando Filtros de Conteúdo no Azure OpenAI

Bem-vindo à exploração dos filtros de conteúdo no Azure OpenAI, uma ferramenta essencial para garantir a responsabilidade e ética ao lidar com modelos de IA generativos. Vamos entender como os filtros padrão e personalizados podem ser utilizados para evitar geração de linguagem prejudicial ou ofensiva.

## Antes de Começar

1. Certifique-se de ter uma assinatura do Azure aprovada para acessar o serviço Azure OpenAI. Caso ainda não tenha, inscreva-se para uma [assinatura gratuita do Azure](https://azure.microsoft.com/free).

2. Solicite acesso ao serviço Azure OpenAI em [aka.ms/oaiapply](https://aka.ms/oaiapply).

## Provisionando um Recurso Azure OpenAI

1. Acesse o [portal do Azure](https://portal.azure.com/).

2. Crie um recurso Azure OpenAI com as configurações necessárias, incluindo um nome exclusivo e o nível de preços padrão S0.

3. Aguarde a conclusão da implantação e acesse o recurso Azure OpenAI no portal do Azure.

## Implantando um Modelo

1. Na página Visão Geral do seu recurso Azure OpenAI, clique em "Explorar" para abrir o Azure OpenAI Studio em um novo navegador ou acesse diretamente [Azure OpenAI Studio](https://studio.openai.azure.com/).

2. No Azure OpenAI Studio, crie uma nova implantação com o modelo gpt-35-turbo, utilizando as configurações padrão.

## Gerando Saída em Linguagem Natural

1. No "Playground do Chat", teste o modelo inserindo o prompt "Describe characteristics of Scottish people". Observe como o modelo gera uma resposta geral e inofensiva.

2. Modifique a configuração para simular um comportamento inadequado, inserindo um prompt indicando que o modelo deve ser racista. Salve as alterações.

3. Insira novamente o prompt "Describe characteristics of Scottish people" e observe como os filtros padrão evitam a geração de conteúdo prejudicial.

## Explorando Filtros de Conteúdo Personalizados

1. No Azure OpenAI Studio, acesse a página "Filtros de Conteúdo".

2. Selecione "Criar Filtro de Conteúdo Personalizado" para revisar as configurações padrão e as opções para personalização.

3. Explore as quatro categorias de conteúdo potencialmente prejudicial: Ódio, Sexual, Violência e Automutilação.

4. Observe como as configurações padrão permitem linguagem de baixa severidade para cada categoria. Entenda que você pode criar filtros mais restritivos, mas não menos restritivos sem permissão específica.

## Limpeza

Quando terminar, lembre-se de excluir a implantação ou o recurso completo no [Portal do Azure](https://portal.azure.com/).

