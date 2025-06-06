# Recebimento e Resposta de Push de Teste no App Proteção Rua

**ID: US-BTC-356**

Descrição: O aplicativo Proteção Rua agora pode receber notificações de teste enviadas pelo BackEnd. Quando o app recebe essa notificação, ele envia uma mensagem de volta para confirmar que tudo ocorreu bem, incluindo um identificador único do dispositivo nesse retorno. Se essa resposta não for enviada com sucesso, o app guarda o erro para tentar novamente mais tarde. Isso ajuda a garantir que as notificações de teste estão funcionando corretamente no celular.