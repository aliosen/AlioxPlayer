# Política de Privacidade - Aliox Player

**Última atualização: 17 de março de 2026**

O **Aliox Player** ("nós", "nosso") está comprometido em proteger sua privacidade. Esta Política de Privacidade explica como lidamos com as informações quando você usa nosso aplicativo, especialmente em relação à integração com o Google Drive.

## 1. Informações que Acessamos e Coletamos

Para funcionar como um player de música em nuvem, o aplicativo solicita acesso ao seu Google Drive através do escopo `drive.readonly`. 

*   **Metadados de Arquivos**: Acessamos nomes de arquivos, IDs, tamanhos e tipos de mídia (áudio) para indexar sua biblioteca de música.
*   **Conteúdo de Áudio**: O aplicativo lê os arquivos de áudio para reprodução e extração de metadados de música (ID3 tags como Artista, Álbum e Capa).
*   **Armazenamento Local**: As informações indexadas (nomes de músicas, artistas e capas de álbuns) são armazenadas **localmente** no seu dispositivo usando tecnologias como IndexedDB (no navegador/app) para permitir o acesso rápido à sua biblioteca.

## 2. Como Usamos as Informações

As informações coletadas são usadas exclusivamente para:
*   Exibir sua biblioteca de música dentro do aplicativo.
*   Permitir a reprodução de seus arquivos de áudio via streaming direto do seu Google Drive.
*   Organizar suas músicas por artista e álbum.

## 3. Compartilhamento de Dados

**Nós não compartilhamos, vendemos ou transferimos seus dados para terceiros.** 
Todos os dados de metadados permanecem no seu dispositivo e as credenciais de acesso (tokens) são gerenciadas de forma segura e enviadas apenas para os servidores oficiais da Google para autenticação.

## 4. Retenção e Exclusão de Dados

*   O aplicativo não possui um servidor próprio; portanto, seus dados não são armazenados em nossos servidores.
*   Você pode remover todos os dados coletados pelo aplicativo a qualquer momento:
    1.  Fazendo **Logout** nas configurações do aplicativo.
    2.  Limpando o cache/dados do aplicativo em seu dispositivo.
    3.  Revogando o acesso do "Aliox Player" através das configurações de segurança da sua Conta Google.

## 5. Requisitos de Uso Limitado da Google

O uso de informações recebidas das APIs do Google pelo Aliox Player seguirá a [Política de Dados do Usuário dos Serviços de API do Google](https://developers.google.com/terms/api-services-user-data-policy), incluindo os requisitos de **Uso Limitado**.

## 6. Contato

Se você tiver alguma dúvida sobre esta política, sinta-se à vontade para abrir uma issue no repositório oficial do projeto no GitHub.
