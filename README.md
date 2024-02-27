# LAB2 IA-900
#### PROJETO PARA CERTIFICAÇÃO MICROSOFT IA-900 DA DIO

![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

> ## Dados sobre o projeto:

- _Crie um novo repositório no github com um nome a sua preferência;_
- _Crie uma pasta chamada 'inputs' e salve as imagens que você utilizou;_
- _Crie uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens;_
- _Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo;_
- _Compartilhe conosco o link desse repositório através do botão 'entregar projeto'._


##
> ### Configurações:
##
   1. #### Criar um recurso de serviços de IA do Azure
      - Abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.
      - Clique no botão *<b> + Criar um recurso </b>* e procure serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure.
         - Assinatura: sua assinatura do Azure.
         - Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
         - Região: Leste dos EUA.
         - Nome: insira um nome exclusivo.
         - Nível de preços: Standard S0.
         - Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo: Selecionado.
      - Selecione Revisar + criar e, em seguida, Criar e aguarde a conclusão da implantação.
   3. #### Conectar seu recurso de serviço de IA do Azure ao Vision Studio
      - Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.
         1. Em outra guia do navegador, navegue até o Vision Studio em https://portal.vision.cognitive.azure.com.
         2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.
         3. Na home page do Vision Studio, selecione Exibir todos os recursos no cabeçalho Introdução ao Vision.
         4. Na página Selecione um recurso para trabalhar, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão.
            ##
            ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/b54da42e-bcf8-445c-994a-8fa337587dfd)

         6. Feche a página de configurações selecionando o "x" no canto superior direito da tela.
            ##
            ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/1de1f476-c8aa-407f-9f77-cc0a1234663c)


##

 >  Detectar rostos no Vision Studio
##
   1. Fiz esse priemiro teste com imagens extraidas do site: https://br.freepik.com/fotos-vetores-gratis/rosto pois são imagens publicas;
   2. Adicionado a pasta com download de três imagens e adicionei a pasta inputs e o resultado do .json;
      ##
      [Figura 1: Teste Rosto01]
      
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/ecc666ef-f72e-410c-8d7a-8bc78a4290a9)
      
      <div align="center">Fonte: freepik.com, 2024.</div>
      ##
      [Figura 2: Teste Rosto02]
      
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/12bc8f0b-c184-4ae7-b5c3-b838bf8ae83a)
      
      <div align="center">Fonte: freepik.com, 2024.</div>
      ##
      [Figura 3: Teste Rosto03]
      
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/cadf6678-2fc2-48e0-84c7-0e8526e2ac31)
      
      <div align="center">Fonte: freepik.com, 2024.</div>
      
      
      

 > Ler texto no Vision Studio
   1. Adicionado a pasta com download de três imagens e adicionei a pasta inputs e o resultado do .json;
   2. Fiz o primeiro teste com letra de um médico tirado do site: https://super.abril.com.br/mundo-estranho/por-que-medico-tem-letra-ruim
      ##
      [Texto 1: Letra de Médico]
      Na tentativa de reconhecimento vi que as palavras em algum ponto não e possível entender.
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/f1bf95c7-1846-4efd-8ba1-258054e79e0e)
       <div align="center">Fonte: super interessante, 2024.</div>


   5. Esta imagem foi tirada do site Baú do Valentim: https://www.baudovalentim.net/a-escrita-a-mao-nao-pode-morrer/
      ##
      [Texto 2: Escrita a mão]
      Textos com letra cursiva notei que o corte de passagem para outra linha não foi entendido.
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/70cb5792-75fd-4038-a9aa-892a739ea78c)
      <div align="center">Fonte: Baú do Valentim, 2024.</div>


   4. Esta imagem foi tirada do site ISTOÉ: https://istoe.com.br/106164_OS+BENEFICIOS+DE+ESCREVER+A+MAO/
      ##
      [Texto 3: Texto Simples]
      Ja em um texto impresso de livros ou criado em aplicativos sua identificação foi satisfatória.
      ![image](https://github.com/vinicius-campelo/lab2-ia900/assets/74797865/91e2961f-28c3-4667-ad28-5e6c668229a7)
      <div align="center">Fonte: ISTOÉ PUBLICAÇÕES LTDA, 2024.</div>

   
      

##
 > Analisar imagens no Vision Studio
##



## Referências:

 - [Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)
 - [Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
 - [Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
 - [SprintAI900: Azure Machine Learning](https://www.youtube.com/watch?v=PzdYcJ1pRPI&t=18s)
 - [IA para Quem não é Cientista de Dados](https://www.youtube.com/watch?v=a4_7HdJ1cys&t=1918s)
