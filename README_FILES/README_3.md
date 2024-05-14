## 3. Configurar Certificados do Jericho 2.3.0-beta

Para configurar os certificados do Jericho 2.3.0-beta, siga as etapas abaixo:

- **Jericho 2.3.0-beta:**
  Coloque os certificados em: `C:\Users\LGEPSCD\jericho\tools\certificados`

- **Instalar os certificados para todos:**
  Certifique-se de ter acesso de administrador para executar os seguintes comandos:

  ```sh
  keytool -importcert -alias des-sts-mbi-cloud-ihf -file "C:\Users\LGFPSCD\jericho\tools\certificados\des-sts-mbi-cloud-íhf.cert" -keystore "C:\Users\LGFPSCD\jericho\tools\jdk17-win\lib\security\cacerts" -storepass changeit

  keytool -importcert -alias gitcorp-prod-aws-cloud-ihf -file "C:\Users\LGFPSCD\Jericho\tools\certificados\gitcorp-prod-aws-cloud-ihf.cer" -keystore "C:\Users\LGFPSCD\jericho\tools\jdk17-win\lib\security\cacerts" -storepass changeit

  keytool -importcert -alias gatewayawsdev -file "C:\Users\LGFPScD\jericho\tools\certificados\gatewayawsdev.cer" -keystore "C:\Users\LGFPSCD\jericho\tools\jdk17-win\lib\security\cacerts" -storepass changeit

Certifique-se de substituir os caminhos dos certificados e do keystore de acordo com sua configuração.
Todos os certificados foram instalados com sucesso.
