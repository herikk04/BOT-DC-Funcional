Discord Music Bot
Este repositório contém o código fonte de um bot de música para Discord desenvolvido em Python. Este bot permite que os usuários do Discord reproduzam músicas diretamente de canais de voz.

Estrutura do Projeto
O projeto está organizado nas seguintes pastas e arquivos principais:

main.py: Script principal que inicializa o bot e gerencia os comandos.
music.py: Script contendo a lógica de reprodução de música.
.env: Arquivo de configuração contendo variáveis de ambiente sensíveis.
requirements.txt: Lista de dependências necessárias para o funcionamento do bot.
Tecnologias Utilizadas
Python: Linguagem principal utilizada no desenvolvimento do bot.
discord.py: Biblioteca usada para interagir com a API do Discord.
python-dotenv: Biblioteca para carregar variáveis de ambiente de um arquivo .env.
PyNaCl: Biblioteca necessária para o suporte a voz no discord.py.
youtube-dl: Ferramenta para download de vídeos do YouTube.
ffmpeg: Ferramenta para manipulação de áudio e vídeo.
Funcionalidades
O bot de música para Discord oferece as seguintes funcionalidades:

Play: Reproduz uma música do YouTube em um canal de voz.
Pause: Pausa a música atual.
Resume: Retoma a reprodução da música.
Stop: Para a música e sai do canal de voz.
Como Executar
Clone este repositório para o seu ambiente local.
bash
Copiar código
git clone <URL_do_repositório>
Navegue até o diretório do projeto.
bash
Copiar código
cd <diretório_do_projeto>
Crie e ative um ambiente virtual.
bash
Copiar código
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
Instale as dependências.
bash
Copiar código
pip install -r requirements.txt
Crie um arquivo .env na raiz do projeto e adicione suas variáveis de ambiente, incluindo o token do seu bot do Discord.
makefile
Copiar código
DISCORD_TOKEN=<seu_token_do_discord>
Execute o script principal.
bash
Copiar código
python main.py
Autores
Herik Kauan De Assis
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para sugerir melhorias ou corrigir problemas.

Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.

