meu-projeto
git init
 - Inicia um novo projeto com Git.

git add <nome do arquivo> .
 - Exemplo: git add arquivo.txt
  - Adiciona os arquivos que estão prontos para serem commitados.

git commit -m "mensagem do commit" 
- Exemplo: git commit -m "Adiciona a funcionalidade X" 
- Comita os arquivos no histórico.

git log 
- Mostra os últimos commits, log de alterações.

git status 
- Mostra o estado das ramificações.

git diff 
- Mostra o que foi alterado, o que tem de alteração nas ramificações.

git merge 
- Mescla ramificações.

git branch 
- Mostra a branch atual.

git branch -b <nome-da-branch>
 - Exemplo: git branch -b nova-funcionalidade 
 - Cria uma branch a partir da branch atual em que estamos.

git checkout <nome-da-branch> 
- Exemplo: git checkout nova-funcionalidade
- Muda para a branch selecionada.

git remote add <nome> <url> 
- Exemplo: git remote add origin https://github.com/usuario/repositorio.git
- Adiciona um repositório remoto.

git push <nome> <nome-da-branch> 
- Exemplo: git push origin main
- Envia nossas alterações locais para o repositório remoto para cada branch.

git pull <nome> <nome-da-branch> 
- Exemplo: git pull origin main 
- Pega as alterações do repositório remoto e traz para nossa máquina.

git fetch 
- Atualiza o histórico local de acordo com o histórico salvo no repositório remoto, sincronizando o local com o remoto.