# Ativação com Token OAuth no App Proteção Rua

**ID da US: US-BTC-72**

No aplicativo Proteção Rua, você pode ativar seu acesso usando um token OAuth. Quando você se autentica com um token válido, recebe um access_token e um refresh_token, que permitem acessar as funções do app. Se o access_token expirar, você poderá usar o refresh_token para conseguir um novo. Se ocorrer algum problema ao tentar ativar, uma mensagem aparecerá informando que houve uma falha. A ativação do app também permite que você troque de dispositivo sem perder o acesso, garantindo que você continue a usar o app normalmente com o novo deviceId.