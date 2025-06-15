# azure-speech-and-language
Repositório de demonstração contendo anotações e insights sobre a inicialização e uso das ferramentas 'Azure Speech Studio' e 'Language Studio', como parte do Curso Integrando com Serviços de IA da DIO ministrado pela professora Valéria Baptista (@baptista.valeria / @canaldacloud).

À medida que formos avançando na utilização da ferramenta, novas demonstrações e recursos serão exibidos nesse repositório.

## CAPACIDADES DE PROCESSAMENTO DE LINGUAGEM NATURAL DO AZURE

### ANALISANDO TEXTO

Vamos analisar o 'Language Studio', o estúdio de linguagem da Microsoft. O propósito desse estúdio é fornecer um conjunto de ferramentas baseadas no cenário de interface do usuário que permita explorar, integrar e criar recursos de linguagem através de uma plataforma que nos traga ideias sobre o que estamos escrevendo.

Se tivermos um texto "passei férias maravilhosas na França", a ferramenta irá extrair o idioma predominante (português), o sentimento (0,88 Positivo), frases-chave (férias maravilhosas) e entidade (França). O Language Studio nos ajuda a classificar o texto com base na compreensão do idioma e na classificação personalizada. Através disso, conseguimos criar um recurso para conseguirmos extrair métricas de textos, nos informem sobre os sentimentos envolvidos nos textos, bem como outras informações semânticas. Isso pode ser utilizado em vários contextos de negócio.

Essa ferramenta também pode ser utilizada para definir uma base de conhecimento de pares de perguntas e respostas a partir de um documento de perguntas frequentes existente, por exemplo, permitindo que um agente de IA interaja com o usuário a partir de um bate-papo integrado.

### SERVIÇO DE BOT DO AZURE

Esse serviço é o mais familiar ao usuário, pois já é utilizado amplamente por várias empresas em vários ramos de negócio em ferramentas de SAC, por exemplo.

O serviço de 'bot' será tão eficiente quanto maior seja sua base de dados. Através de palavras-chave ou frases-chave contidas na pergunta do usuário que o agente de IA buscará as informações que estão sendo solicitadas.

É muito importante testar constantemente a base de conhecimento e deixá-la sempre atualizada para evitar que o usuário deixe de ser atendido em sua solicitação, o que se traduz numa falha da própria ferramenta.

Para tanto, o Serviço de Bot do Azure disponibiliza uma plataforma baseada em nuvem para desenvolvimento e gerenciamento dos 'bots', trazendo integração com AI Language e outros serviços além de conectividade através de vários canais (seja aplicativo, site, email ou telefone) com o usuário.

### COMPREENSÃO DA LINGUAGEM COLOQUIAL

A linguagem coloquial é a linguagem dos diálogos do dia a dia. A compreensão desse modelo de linguagem é formado por três componentes principais:

- Declaração: é o enunciado do que se pede que seja feito.

- Entidade: é o item específico da mensagem. 

- Intenção: é o que identifica a ação que se busca.

### RECONHECIMENTO E SÍNTESE DE FALA

É um serviço de conversão de texto em fala para gerar fala audível a partir de um texto, ou o contrário. Isso é útil tanto num cenário de inclusão de alguém com limitação de visão ou então apenas para gerar mais praticidade (utilização no trânsito, por exemplo).

### CONHECENDO O ESTUDIO DE FALA

(Veja também: http://aka.ms/ai900-speech)

O Portal Estúdio de Fala da Microsoft pode ser acessado pelo link:

https://speech.microsoft.com/portal

Essa funcionalidade serve para fazermos o upload de um arquivo de áudio a ser transcrito pela ferramenta. Ou, ainda, podemos inserir um arquivo de texto e a ferramenta irá gerar um arquivo de voz com o que foi escrito.

Para fazermos isso, clicamos no ícone de engrenagem situado na barra superior direita do site para abrir as 'Configurações' do Estúdio de Fala. Então clicamos em 'Recurso' na barra superior esquerda e depois no botão '+ Criar novo recurso'.

No pop-up que abrir, colocaremos um nome para o recurso, selecionamos uma assinatura (ou criamos uma).

Selecionamos uma região, o tipo de preço ('S0') e um grupo de recursos.

Feito isso, já estamos aptos a usar o serviço, mas é preciso deixá-lo selecionado. Para finalizar, clicamos no botão inferior esquerdo do site 'Usar o recurso'. Então, fechamos a página de 'Configurações' clicando no 'X' no canto superior direito da página.

Na seção 'Conversão de fala em texto', selecionamos a primeira opção: 'Conversão de fala em texto em tempo real'.

É importante deixar marcada a opção "Reconheço que este aplicativo usa o recurso 'xxxxx' e incorrerá em uso para a minha conta", onde 'xxxxx' é o recurso que criamos.

Então selecionamos o idioma do arquivo que vamos importar no site clicando no menu 'Escolher um idioma' e, mais abaixo, clicamos em 'Procurar arquivos' na seção 'Escolher os arquivos de áudio'.

Após selecionarmos o arquivo de áudio que queremos converter em texto, a ferramenta já começará a fazer a transcrição no campo 'Resultados de teste'.

A partir daí, na seção 'Próximas etapas', clicamos em 'Introdução' no menu lateral esquerdo e podemos ver as configurações para utilizar o Serviço Cognitivo do Azure como uma API de fala. É nesse local que conseguimos o link e a chave de acesso ao recurso.

Ainda na seção 'Próximas etapas', temos no menu lateral a opção 'Cenários comuns', que nos permite experimentar a função de legenda automática de um conteúdo em tempo real ou offline, que serve para transcrever o áudio de filmes, vídeos, eventos ao vivo e muito mais. Também disponibiliza a transcrição e análise de 'Call Center', permitindo transcrever em lote as gravações de um centro de atendimento telefônico e extrair informações valiosas, como informações de identificação pessoal (PII), sentimento e resumo de chamada.

Na terceira opção 'Serviços relacionados', podemos iniciar um projeto de "Fala personalizada", onde podemos melhorar a precisão da conversação de fala em texto da Microsoft para aplicativos e produtos, adaptando ao vocabulário do aplicativo e ao estilo de fala dos usuários.

Ainda nos 'Serviços relacionados', experimentar a "Galeria de Voz" para escolher dentre 400 vozes em 140 idiomas e variantes, para customização de cenários através de vozes expressivas e naturais.

Também a "Avaliação de Pronúncia" é disponibilizada para que alunos de idiomas possam praticar, obter comentários e melhorar a pronúncia.

A quarta opção nos traz links para verificarmos os preços desses serviços e uma calculadora de preços para utilização dos serviços do Azure. Além disso, é disponibilizado um botão para entrarmos em contato com um especialista de vendas.

E a quinta opção do menu 'Serviços relacionados' traz a política de responsabilidade de uso.

### CONHECENDO O LANGUAGE STUDIO

(Veja também: http://aka.ms/ai900-text-analysis)

O Language Studio da Microsoft pode ser acessado pelo link:

A ferramenta do Language Studio vai nos ajudar a fazer uma análise semântica de texto ou de fala, análise de sentimentos etc. É um ramo da IA que nos ajudará a interpretar mensagens e textos.

O primeiro passo é acessarmos o link 'https://portal.azure.com' com uma conta Microsoft e clicamos em 'criar um recurso', selecionamos a categoria 'AI + Machine Learning' e clicamos em 'Serviço de Linguagem' ('Language Service').

Conferimos se as "features" (características) padrão estão todas selecionadas e clicamos em 'Continuar para criar um recurso'.

Na próxima tela, 'Create Language', selecionamos como 'Resource Group' a opção 'LABAI-900'; em 'Instance Details' colocamos "idiomalanguage" como 'Name', escolhemos 'Free F0' como 'Pricing tier', marcamos a opção 'By checking this box I certify that I have reviewed and acknowledge the terms in the Responsible AI Notice' e, por fim, clicamos em 'Review + create'.

Após um tempo de validação, o botão 'Create' será disponibilizado para que possamos finalmente criar o recurso.

Finalizada a criação, teremos uma página para gerenciamento do nosso recurso 'LABAI-900'.

Em outra aba do nosso navegador, abrimos o link 'language.cognitive.azure.com' do Language Studio da Azure AI e logamos com nossa conta Microsoft. Finalizando o "logon", o site nos pedirá para selecionarmos um recurso da Azure.

Preenchemos os campos definindo, no último campo, o recurso "idiomalanguage" que criamos anteriormente e clicamos em 'Done'.

O próximo passo agora é criarmos um projeto clicando em 'Classify text' na barra de recursos localizada abaixo da mensagem de boas vindas. Agora clicamos no "card" 'Analyze sentimento and mine opinions'.

Na tela seguinte de utilização do recurso, deixamos como idioma selecionado o inglês e conferimos o recurso "idiomalanguage" já definido para utilização.

Nessa página podemos inserir um texto digitado, fazer 'upload' de um arquivo ou usar um texto de exemplo para testar a ferramenta.

Depois de colocado o texto ou feito o upload do arquivo, marcamos a opção 'I acknowledge that running this demo will incur usage and may incur costs to my Azure resource' e clicamos no botão 'Run'.

Abaixo haverá um campo mostrando o resultado da análise do texto ou arquivo disponibilizado.

### Documentações Oficiais

Laboratórios no Microsoft Learning:

- [Explore Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
- [Analyze Text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
