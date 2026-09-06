# NexAvalia — distribuição oficial

Instaladores e dados públicos de atualização do aplicativo NexAvalia para Windows 10/11 de 64 bits. Este repositório não contém o código-fonte do aplicativo nem credenciais de clientes ou da administração.

## Instalar ou atualizar

1. Abra a [versão mais recente](https://github.com/jonatashonorioferraz/nexavalia-releases/releases/latest).
2. Baixe o arquivo **Instalar_NexAvalia_vVERSAO.exe**, na seção Assets/Arquivos.
3. Pare o agente e feche as janelas da NexAvalia antes de executar o instalador.
4. Não é necessário desinstalar a versão anterior. Seu acesso, configurações e histórico são preservados.

A partir da versão **0.10.0**, o botão **Verificar atualizações**, no canto superior direito do programa, consulta este canal. Quando uma versão nova for publicada, escolha **Baixar atualização** e depois **Instalar e reabrir**. Com a versão mais recente instalada, o aplicativo informa que está atualizado.

O arquivo `latest.json` é usado pelo aplicativo para autenticar e verificar o download. Não é necessário abri-lo manualmente. A assinatura do canal de atualização não é um certificado Authenticode; o instalador ainda não tem certificado de publicador Windows.

O download não concede uma licença: o código do cliente e a chave de acesso são fornecidos separadamente pela administração da NexAvalia. Nunca compartilhe sua chave em comentários ou issues públicas.
