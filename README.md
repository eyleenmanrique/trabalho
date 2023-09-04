<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>TRABALHO</title>
		<link rel="stylesheet" href="style.css">

	

		<h1 style="text-align: center">TRABALHO</h1>
 
		<p> <strong>1)Explique o que é o Git e por que é amplamente utilizado no desenvolvimento de software.</strong> 
		    R:O Git é um projeto de código aberto maduro e com manutenção ativa desenvolvido em 2005 por Linus Torvalds, o famoso criador do kernel do sistema operacional Linux..</p>

		<p><strong>2)Quais são as principais diferenças entre Git e outros sistemas de controle de versão centralizados?</strong>
			R:Assim que um arquivo é versionado, uma versão é criada e pode ser incrementada e trabalhada durante o ciclo de vida do repositório. A principal diferença do Git para outras ferramentas de controle de versão é a maneira com que os dados são trabalhados. </p>

		<p><strong>3)Descreva o fluxo de trabalho básico no Git, desde a criação de um repositório até a realização de commits e pushs.</strong>
			R:1-Instalação do Git: Antes de começar, você deve instalar o Git em seu sistema. Você pode fazer isso baixando e instalando-o a partir do site oficial.2-Configuração Inicial: Após a instalação, é importante configurar seu nome de usuário e endereço de e-mail. Isso é feito usando os seguintes comandos, que precisam ser executados apenas uma vez:<strong>git config --global user.name "Seu Nome"</strong>
			<strong>git config --global user.email "seu@email.com"</strong>.3-Criação de um Repositório: Agora você pode criar um novo repositório Git ou clonar um existente. Para criar um novo repositório, vá para o diretório do projeto e execute:<strong>git init</strong>.4-Realização de Commits: Após adicionar os arquivos, você deve criar um commit para registrar as alterações. Um commit é uma captura instantânea das alterações. Use o seguinte comando:<strong>git commit -m "Mensagem descritiva do commit"</strong>.5-Push para um Repositório Remoto: Se você estiver trabalhando com um repositório remoto (como no GitHub), pode enviar suas alterações para ele usando o comando:<stong>git push origin nome_do_branch</stong></p>

		<p><strong>4)Explique como configurar o Git em seu computador e como criar um novo repositório local.Demonstre os comandos básicos do Git para: a) Adicionar arquivos ao staging area. b) Realizar commits. c) Criar e alternar entre branches. d) Mesclar branches. e) Resolver conflitos de merge.</strong>
			R:a) Adicionar arquivos ao staging area:Use o comando git add para adicionar arquivos ao staging area. Por exemplo, para adicionar um arquivo chamado "meuarquivo.txt":<strong>git add meuarquivo.txt</strong>Para adicionar todos os arquivos modificados ao staging area, use:<strong>git add.</strong>. 
			b) Realizar commits:Use o comando git commit para criar um commit com as alterações no staging area e uma mensagem descritiva:<strong>git commit -m "Mensagem descritiva do commit"</strong>. 
			c) Criar e alternar entre branches: Para criar um novo branch:<strong>git branch nome_do_branch</strong>. Para alternar para um branch existente:<strong>git checkout nome_do_branch</strong>. Para criar um novo branch e alternar para ele em uma única etapa:<strong>git checkout -b nome_do_branch</strong>. 
			d) Mesclar branches:Primeiro, certifique-se de estar no branch para o qual deseja mesclar as alterações. Por exemplo, para mesclar as alterações do branch "feature" no branch "main":<strong>git checkout main</strong>. Em seguida, execute o comando git merge:<strong>git merge feature</strong>
			e) Resolver conflitos de merge: Se houver conflitos de merge ao tentar unir dois branches com alterações conflitantes, você precisará resolvê-los manualmente. Abra os arquivos em um editor de texto e resolva os conflitos, removendo as linhas desnecessárias e mantendo as alterações desejadas. Após resolver os conflitos, adicione os arquivos novamente ao staging area com git add e, em seguida, crie um commit para finalizar o merge com git commit.
			Esses são os comandos básicos do Git para criar e gerenciar um repositório local, adicionar arquivos ao staging area, realizar commits, criar e alternar entre branches, mesclar branches e resolver conflitos de merge. Esses comandos são fundamentais para trabalhar eficazmente com o Git em projetos de desenvolvimento de software.
	</body>
</html>
