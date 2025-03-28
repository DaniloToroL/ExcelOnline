


## How to use this module

Before using this module, you must register your app into the Azure Portal.

Registration:

1. Sign in to Azure Portal. Then go to the next link: https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade (App Registrations).
2. Click on "New registration". Choose a name.
3. In “Supported account types” choose "Accounts in any organizational directory (Any Azure AD directory - Multitenant) and personal Microsoft accounts (e.g. Skype, Xbox)".
4. In "Redirect URI" select "Web" as a plataform and set the URI to: https://localhost/. Finally click on "Register"
5. Once registered, on the "Overview" section you will find the "Application (client) ID", write it down/save it, you will need it later.
6. Go to "Certificates & secrets", generate a "New client secret", write a description and set the expration time to 24 months (preferably). Click on "Add" and write down/save the "Value" (NOT the "Secret ID"), you will need it later together with the App ID.
7. Finally, go to "API persmissions", click on "Add a permission", then on "Microsoft Graph" and select "Delegated permissions". In the search bar type "Files.ReadWriteAll", mark the checkbox and click on "Add permissions".

---

## Como usar este modulo

Antes de usar este modulo, es necesario registrar tu aplicación en el portal de Azure. 

Registración: 

1. Inicie sesión en el portal de Azure. Luego diríjase al siguiente link: https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade (Registración de Aplicaciones). 
2. Click en "Nueva Registración". Elija un nombre. 
3. En "Tipo de Cuentas" elija "Cuentas de cualquier directorio de la organización y cuentas personales de Microsoft (por ejemplo, Skype, Xbox)". 
4. En "URI de Redirección" selecciones "Web" como plataforma y ponga como URI: __https://localhost/__. Finalmente clieckear en "Registrar". 
5. Una vez registrada, en la sección "General" encontrara el "ID de Aplicación (Cliente)", escriba/guárdelo, lo necesitara mas adelante. 
6. Diríjase a "Certificados y Secretos", genere un nuevo "Secreto de Cliente", escriba una descripción y fije la expiración en 24 meses (preferiblemente). Click en "Adherir" y escriba/guarde el "Valor" (NO el "ID de Secreto"), lo necesitara luego junto con el ID de la App. 
7. Finalmente, vaya a "Permisos de API", clickee en "Adherir permiso", luego en "Microsoft Graph" y seleccione "Permisos delegados". En la barra de búsqueda tipee, "Files.ReadWriteAll", marque con un tilde el casillero y clickee en "Adherir Permisos". 

---

## Como usar este módulo

Antes de usar este módulo, você deve registrar seu aplicativo no Portal do Azure.

Cadastro:

1. Entre no Portal do Azure. Em seguida, vá para o próximo link: https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade (Registros de aplicativos).
2. Clique em "Novo registro". Escolha um nome.
3. Em "Tipos de conta compatíveis", escolha "Contas em qualquer diretório organizacional (qualquer diretório do Azure AD - Multilocatário) e contas pessoais da Microsoft (por exemplo, Skype, Xbox)".
4. Em "Redirect URI" selecione "Web" como plataforma e defina o URI para: https://localhost/. Por fim, clique em "Registrar"
5. Uma vez cadastrado, na seção "Visão geral" você encontrará o "ID do aplicativo (cliente)", anote/salve-o, você precisará dele mais tarde.
6. Vá em "Certificados e segredos", gere um "Novo segredo de cliente", escreva uma descrição e defina o tempo de expração para 24 meses (de preferência). Clique em "Add" e anote/salve o "Value" (NÃO o "Secret ID"), você precisará dele mais tarde junto com o App ID.
7. Por fim, vá em "Permissões de API", clique em "Adicionar uma permissão", depois em "Microsoft Graph" e selecione "Permissões delegadas". Na barra de pesquisa digite "Files.ReadWriteAll", marque a caixa de seleção e clique em "Adicionar permissões".