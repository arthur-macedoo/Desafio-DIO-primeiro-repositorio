  # Repositório do Desafio de Projeto Git/Github da DIO

 Nesse projeto você irá aprender a:

- [ ] Criar um repositório no GitHub;
- [ ] As dinâmicas possíveis que podemos fazer com esse repositório;
- [ ] Baixá-lo em nossa máquina;
- [ ] Fazer edições de um repositório pelo GitHub e sincronizá-lo com nossa máquina;
- [ ] Fazer edições locais do repositório em nossa máquina e sincronizá-la com o GitHub;

## Como criar um repositório? 🤨

Bem, para começar, você deve ter uma conta no GitHub. Para criar uma, basta acessar esse [link](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).

Ok! Conta criada, procure por um símbolo de "+" no canto superior direito no topo do site. Provavelmente, deve ser mais ou menos assim:
<p align="center">
   <img src="/img/Screenshot_1.png" alt="Novo Repositório">
</p>

Na aba de criação do novo repositório, você pode colocar qualquer nome que quiser! Mas atenção, é importante que o nome do seu repositório seja sugestivo ao seu trabalho, ok!? Feito isso, na aba de descrição do repositório, você pode colocar uma explicação ou breves informações sobre seu repositório (opcional).

Quanto a privacidade do seu repositório, ao deixar público, todos os usuários do GitHub poderão ter acesso a ele. Já o privado, apenas você ou pessoas selecionadas podem acessá-lo. É recomendado que o repositório seja quase sempre público, pois assim, mais pessoas e até empresas podem conhecer mais sobre seus projetos, além de receber feedbacks de outros usuários sobre eles.


Opcionalmente, você pode criar também em seu repositório arquivos como o README e .gitignore além de possíveis licensas que esse repositório tiver.

### README 📑

O README é um arquivo super útil que pode ter várias funções! Podemos usá-lo para fazer considerações iniciais, possíveis instruções para instalação ou uso do repositório, anotações (como essa kkkkkkk), links úteis ou algo relevante a ser escrito.

### .gitignore ✖️

O .gitignore é um arquivo que pode ser inserido em projetos para que o Git ignore eventuais arquivos que não são essenciais para versionamentos de código.

Agora com seu repositório criado, você tem a possibilidade de coletar as informações dele para clonar em sua máquina local para trabalhar com ele, além de várias possibilidades, como usá-lo como site (caso seja um repositório em HTML, por exemplo).

## Dinâmicas com seu novo repositório 💡

Ao clicar em um determinado arquivo, abre-se uma aba no GitHub de todo o código dele. Nela, você pode fazer eventuais correções que não foram feitas anteriormente ou até montar do zero uma linha de código! Porém é importante saber que para que essas novas informações sejam salvas, você precisa commitá-las em "Commit changes", um botão que fica bem ao final da página na cor verde.

Ok, mas como posso pegar esse repositório e trabalhar com ele localmente? É simples!

## Como baixar um repositório em uma máquina local? :disappointed_relieved:

Existem várias formas de realizar o download de um repositório no GitHub. Uma delas seria criando um arquivo ZIP, que ao acessar a aba "Code" em verde você consegue localizar essa função.

<p align="center">
   <img src="/img/Screenshot_2.png" alt="Arquivo_zip">
</p>

Além disso, você pode usar a opção clone do Github que está disponível em opções HTTPS, SSH e GitHubCLI.

### HTTPS 🖥️

Para usar o Git clone em HTTPS, basta criar uma pasta em seu computador para guardar todo o repositório, abrir o Git Bash nela [(caso não tenha, entenda como baixar aqui)](https://www.webdevdrops.com/git-bash-como-instalar-usar/) e usar o comando "git clone" com a URL que você copiou no GitHub.

### SSH 🔑

Para usar o Git clone em SSH (um nova forma de autenticação do GitHub, mais segura e com criptografia de ponta a ponta), primeiro deve-se criar uma nova chave com sua máquina e depois, acessá-la em sua conta no GitHub em Configurações>SSH e chaves GPG. Feito isso, basta usar a função "git clone" com a cópia da URL SSH disponível do GitHub e confirmar sua ação.

## Edições locais do repositório em nossa máquina e sincronizá-la com o GitHub 🌐

Baixado o repositório e feita todas as mudanças desejadas, basta usar a função "git add ." ou "git add -A", para salvar suas alterações para mostrar ao Git que você deseja salvá-las. Após isso é usada a função 'git -m "(com um comentário aqui para mostrar o que alteramos ao commitar)"' e em seguida o "git push" para enviar todo o novo conteúdo para o GitHub!

## Links para saber mais sobre Markdown e edições desse tipo de arquivo: ⤵️
[Sintaxe Básica do Markdonw](https://www.markdownguide.org/basic-syntax/) <br>
[Emojis disponíveis para uso no Markdown](https://gist.github.com/rxaviers/7360908)
