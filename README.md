Funcionalidades
Consumo da API do YouTube para buscar vídeos de um canal específico.
Exibição dos vídeos em uma interface web amigável e responsiva.
Informações exibidas incluem o título do vídeo, descrição, miniatura, link e data de publicação.
Ordenação dos vídeos por data de publicação, do mais recente ao mais antigo.
Tecnologias Utilizadas
ASP.NET Core MVC
C#
API do YouTube (Google.Apis.YouTube.v3)
HTML/CSS para a interface de usuário
Pré-requisitos
.NET 6 SDK ou superior
Chave de API do YouTube válida
Como Executar o Projeto
Clone o repositório para o seu ambiente local:

bash
Copiar código
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar código
cd nome-do-repositorio
Configure sua chave de API do YouTube no código (HomeController.cs):

csharp
Copiar código
var youtubeService = new YouTubeService(new BaseClientService.Initializer
{
    ApiKey = "SUA_CHAVE_API",
    ApplicationName = "ApiYoutubeVideo"
});
Execute o projeto:

bash
Copiar código
dotnet run
Acesse a aplicação no navegador através de https://localhost:5001.
