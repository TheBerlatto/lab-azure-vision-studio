# Reconhecimento Facial e imagens no Azure AI Vision Studio

Olá a todos! O objetivo desse repositório é descrever o passo a passo sobre as soluções de visão que geralmente exigem IA para serem capazes de detectar rostos humanos.

Isso faz parte do Desafio de Projeto do curso "Microsoft Azure AI Fundamentals" em parceria com a [DIO](https://dio.me)!

## 👣 Passo a Passo para criar um recurso de serviços de IA do Azure
1. Em outra guia do navegador, abra o [Portal do Azure](https://portal.azure.com), entrando com a conta da Microsoft associada à sua assinatura do Azure.
2. Clique no botão **+Criar um recurso** e procure serviços de IA do Azure. Selecione criar um plano de serviços de IA do Azure. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
- Assinatura: sua assinatura do Azure.
- Grupo de recursos: selecione ou crie um grupo de recursos com um nome exclusivo.
- Região: Leste dos EUA.
- Nome: insira um nome exclusivo.
- Nível de preços: Standard S0.
- **Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo:** Selecionado.
3. Selecione Revisar + criar e, em seguida, Criar e aguarde a conclusão da implantação.

## 👣 Passo a Passo para conectar seu recurso de serviço de IA do Azure ao Vision Studio
1. Em outra guia do navegador, navegue até o [Vision Studio](https://portal.vision.cognitive.azure.com)
2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.
3. Na home page do Vision Studio, selecione **Exibir todos os recursos** no cabeçalho **Introdução ao Vision.**

4. Na página **Selecione um recurso para trabalhar**, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione **Selecionar como recurso padrão.**
5. Feche a página de configurações selecionando o "x" no canto superior direito da tela.

## 👣 Passo a Passo para detectar rostos no Vision Studio
1. Em um navegador da Web, navegue até o [Vision Studio](https://portal.vision.cognitive.azure.com)
2. Na página inicial **Introdução ao Vision**, selecione a guia **Rosto** e selecione o bloco **Detectar faces em uma imagem.**
3. No subtítulo **Experimentar**, reconheça a política de uso de recursos lendo e marcando a caixa.
4. Selecione cada uma das imagens de amostra e observe os dados de detecção de rosto retornados.
5. Explore! Tente fazer o upload de suas imagens próprias.

## 👣 Passo a Passo para extrair texto de imagens no Vision Studio

1. Volte a página inicial **Introdução ao Vision**, selecione **Reconhecimento óptico de caracteres** e, em seguida, o bloco **Extrair texto de imagens**.
2. No subtítulo **Experimentar**, reconheça a política de uso de recursos lendo e marcando a caixa.
3. Teste como quiser selecionando as imagens pré inseridas ali, ou fazendo **upload** de imagens do seu computador.