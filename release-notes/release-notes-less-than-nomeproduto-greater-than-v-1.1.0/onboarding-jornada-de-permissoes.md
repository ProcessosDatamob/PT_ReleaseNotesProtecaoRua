# Onboarding - Jornada de Permissões

Nesta versão, implementamos o novo fluxo de **Onboarding** conforme solicitado. Ao iniciar o aplicativo, você terá a opção de conceder as **permissões necessárias** imediatamente ou optar por fazer isso depois. Se a permissão nativa do sistema operacional não for concedida ou uma opção diferente da ideal para o app for selecionada, uma **tela explicativa (Sheet)** será exibida.

Essa tela destacará a **importância da permissão** e guiará você para a opção correta a ser selecionada. Você terá duas opções:

* **"Continuar"**: Ao selecionar esta opção, você será direcionado(a) diretamente para as **Configurações do seu aparelho** para conceder a permissão correta.
* **"Fazer Depois"**: Se você optar por "Fazer Depois", poderá continuar o fluxo de ativação do app. No entanto, a pendência de permissão será sinalizada na **Home do aplicativo** através de um **card de incentivo**, lembrando-o(a) de ajustar suas permissões posteriormente.

Com essa atualização, buscamos oferecer mais flexibilidade e clareza na gestão das permissões.\


{% hint style="info" %}
_No iOS encontramos uma limitação técnica, devido a uma regra da Apple. Portanto ao testar esta permissão nesta versão, para que sigam o fluxo sem problemas, devem selecionar a opção " Permitir durante o uso do app". Já estamos trabalhando na solução de contorno._
{% endhint %}

{% hint style="info" %}
_A funcionalidade de exibir a tela de permissões pendentes ao clicar no card da Home, será entregue na versão 1.2.0_
{% endhint %}
