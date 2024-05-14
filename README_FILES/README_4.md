## 4. Configuração no IntelliJ IDEA

Para configurar o IntelliJ IDEA, siga as etapas abaixo:

1. Abra o IntelliJ IDEA.
2. Vá para `Settings > Build, Execution, Deployment > Build Tools > Gradle`.
3. **Configurar o Gradle no IntelliJ IDEA:**

   3.1. Gradle user home: `C:/Users/seuRACF/Jericho/tools/gradle-win`.

   3.2. Use Gradle from: gradle-wrapper.properties File.

   3.3. Gradle JVM: Ecplise Temurin version 17.

   3.4. Clique em "Apply".

4. **Configurações do Projeto:**

   4.1. SDK: Ecplise Temurin version 17.

   4.2. Language level: 17 - Sealed types, always-strict floating-point semantics.

   4.3. Clique em "Apply".

5. Para executar o IntelliJ IDEA, rode o Gradle:

    - `gradle --configuration-cache`

    - `gradle --build-cache`

    - Clique em Run 'Application' para rodar o Gradle.
