# modulo3-lab-dio-resumo
Este repositório contem as lições aprendidas durante o desenvolvimento do lab-DIO-AZURE

## Análise do texto e identificação do sentimento do usuário sobre determinado produto ou serviço

### Serviço de bot do Azure

- normalmente utilizado no atendimento inicial ao usuário, possibilitando resolver diversas requisições de forma mais eficiente, já que uma pessoa não conseguiria suprir uma grande demanda com rapidez. Dessa forma, o atendente humano passa a lidar apenas com problemas mais personalizados.

### Compreensão da linguagem coloquial

- utiliza recursos de fala para transcrever áudio em texto.
- Interpreta a fala ou o texto e os converte, tornando as tarefas mais práticas e auxiliando pessoas com deficiência física.

![criando-recurso](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-criando-recurso.png)

- Primeiro, é necessário criar um recurso acessando a área de configurações, definindo a assinatura, o nome do recurso, a região, o tipo de preço e o grupo de recursos.

- Em seguida, selecione o recurso e feche a página de configurações.

![converter-texto](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/sppech-convertendo-audio.png)

![converter-texto2](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/sppech-convertendo-audio2.png)

- Escolha a opção “Conversão de fala em texto em tempo real”. Depois, selecione o recurso novamente e defina o idioma que será utilizado.

- Anexe o áudio, que será convertido automaticamente em texto.

![introducao](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-introducao.png)

- Para utilizar, é preciso configurar o recurso de fala na seção “Introdução”

![servicos-relacionados](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-servicos-relacionados.png)

- Em “Cenários comuns”, são apresentadas situações em que a conversão de fala em texto pode ser aplicada.

![preco](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-preco-servico.png)

- A seção “Serviços relacionados” permite personalizar o vocabulário, definir vozes diferentes e receber feedbacks para avaliar a necessidade de melhorias.
  
- Também é exibido o preço do serviço escolhido.

![lgpd](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-lgpd.png)

- Em “Uso responsável da IA”, são apresentadas informações sobre a LGPD e a segurança de dados sensíveis.

![azure-ia](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/speech-azure-video-ia.png)

- O “Azure Video Indexer” permite extrair insights e gerar legendas a partir de vídeos.

### Language Studio

- Interpreta textos e mensagens.

- É utilizado para avaliar o feedback de usuários por meio de palavras-chave, ajudando a identificar pontos de melhoria.

### Criando um Language Service

![recurso-idioma](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-criar.png)

- Define-se o grupo de recursos, a região, o nome, o plano de preços e a aplicação. Os campos não personalizados seguem as configurações padrão.

![criando-analise](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-analise-sentimento.png)

![criando-analise2](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-analise-sentimento2.png)

![criando-analise3](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-analise-sentimento3.png)

- Acesse o site de Linguagem Cognitiva do Azure e selecione o recurso de linguagem previamente criado.

- Dentro da plataforma, em Linguagem Cognitiva, selecione a opção de Classificação de Texto (Classify Text), e depois acesse Análise de Sentimentos e Opiniões (Analyze Sentiment and Mine Opinions).

- Em seguida, defina o idioma e o recurso do Azure. Depois, basta inserir o texto e executar a análise.

- O sistema retorna os resultados da análise com base nas palavras-chave.

![started](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-started.png)

- Caso deseje utilizar o recurso continuamente, há a opção de criação.

![code](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-code.png)

- Também é possível realizar análise de código.

![servico-preco](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-servico-preco.png)

- São apresentados os tipos de serviço de cobrança disponíveis.

![lgpd](https://github.com/TiagoFerreirago/modulo3-lab-dio-resumo/blob/main/images/language-cognitive-lgpd.png)

- A plataforma informa as políticas de segurança, incluindo LGPD e tratamento de dados sensíveis.

