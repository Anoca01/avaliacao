Explicar como criar um emulador no android estúdio:
-Abra o Android Stduidio, na tela inicial aperte em 'More Actions' depois em Virtual Device Manager ai depois caso nao tenha o seu phone la voce cria, no simbolo de '+' no canto superior direito da tela, ai escolhe o seu celular e aperta em 'next' ate voltar para a tela do '+', depois voce so aperta do simbolo de play.

---------------

Como habilitar o SDK:
Primeiro ir no Android Studio e ir em: More Options > SDK Manager > SDK Tools e instalar o NDK e Android SDK Command
Depois de instalado no seu projeto dentro da pasta android crie um arquivo chamado local.properties e coloque
sdk.dir=C:\\Users\\seuusuario\\AppData\\Local\\Android\\Sdk
Logo após abra o powershell e copie e cole:
cd "C:\Users\seuusuario\AppData\Local\Android\Sdk\cmdline-tools\latest\bin"
.\sdkmanager.bat --licenses
 E aceite todas as solicitações que irá aparecer!

---------------

Como configurar o **ANDROID_HOME** e **JAVA_HOME** nas variáveis de ambiente da sua conta:
Procure no seu pc 'editar as variaveis de ambiente para a sua conta' depois a apertar em 'novo' e definir o nome da sua variavel, no caso 'ANDROID_HOME' ou 'JAVA_HOME' logo em seguida coloque o valor da variável, para o NADROID_HOME coloque 'C:\User\seuusuario\AppData\Local\Android\Sdk' e para o JAVA_HOME 'C:\Program Files\Java\jdk-23

---------------

Como fazer para abrir o projeto no emulador:
Para abrir o projeto no seu emulador, voce precisa estar com o emulador aberto, em seguida no seu projeto no vscode abra o terminal e digite 'npm run android' depois aperte em 'a' e depois abrira no seu emulador o seu projeto.