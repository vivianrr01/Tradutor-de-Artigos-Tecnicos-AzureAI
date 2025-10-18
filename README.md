# Tradutor-de-Artigos-Tecnicos-AzureAI

## Como Utilizar o Código

    Configure suas Credenciais: Substitua "SUA_CHAVE_DE_API_AQUI", "SEU_PONTO_DE_EXTREMIDADE_AQUI" e "SUA_REGIAO_AQUI" pelas informações do seu recurso de Tradutor no Azure.

    Execute a Célula: Em seu Jupyter Notebook, execute a célula com o código acima.

    Insira o Texto: O programa solicitará que você insira o texto técnico a ser traduzido.

    Visualize o Resultado: O idioma do texto de entrada será detectado e, em seguida, a tradução para o português será exibida.

## Garantindo a Precisão Terminológica com um Modelo Customizado

Para projetos que exigem alta fidelidade na tradução de termos técnicos, a criação de um modelo customizado é fundamental. O processo, em linhas gerais, é o seguinte:

    Acesse o Portal do Custom Translator: Utilize o portal do Azure para acessar a ferramenta Custom Translator.

    Crie um Workspace e um Projeto: Organize seus modelos de tradução em workspaces e projetos.

    Faça o Upload de Documentos: Alimente o seu projeto com documentos paralelos (texto de origem e sua respectiva tradução), glossários com termos específicos e seus equivalentes no idioma de destino. Quanto mais dados de alta qualidade você fornecer, melhor será o desempenho do modelo.

    Treine o Modelo: Inicie o processo de treinamento. O Azure AI utilizará seus dados para criar um modelo de tradução neural ajustado ao seu domínio.

    Obtenha o Category ID: Após o treinamento bem-sucedido, o seu modelo receberá um "Category ID".

    Utilize o Modelo na sua Aplicação: Conforme demonstrado na função traduzir_texto, você pode passar esse "Category ID" para garantir que suas traduções utilizem o seu modelo customizado, assegurando a precisão terminológica desejada.
