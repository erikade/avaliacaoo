Emulador android: vc aperta em more actions depois em virtual Device manager e depos aperta no "+" e escolha qual celular vc vai querer e depois so configurar com as suas opçoes e depois so dar start.

Como habilitar o SDK:More Options > SDK Manager > SDK Tools e instalar o NDK e Android SDK Command
 
Depois de instalado no seu projeto dentro da pasta android crie um arquivo chamado local.properties e coloque
sdk.dir=C:\\Users\\seuusuario\\AppData\\Local\\Android\\Sdk
 
Logo após abra o powershell e copie e cole:
cd "C:\Users\seuusuario\AppData\Local\Android\Sdk\cmdline-tools\latest\bin"
.\sdkmanager.bat --licenses

 E aceite todas as solicitações que irá aparecer!

 ANDROID_HOME: Vc abre as ariáveis de ambiente e digita C:\Users\seuUuario\AppData\Local\Android\Sdk
 JAVA_HOME: C:\Program Files\Java\jdk-23

 Como abrir o proejto: vc vai no seu terminal e escreva NPM RUN ANDROID#   a v a l i a c a o o  
 