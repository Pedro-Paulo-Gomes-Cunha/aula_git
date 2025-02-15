# aula_git

## Comandos Fundamentais
  # Clonar um repositório
    # git clone <link_do_repositório>
      Este comando copia um repositório remoto (na nuvem) para a sua máquina local, permitindo que você trabalhe no projeto.
  
  # Verificar o status
    # git status
      Mostra as alterações feitas nos arquivos desde o último commit, indicando quais arquivos foram modificados, adicionados ou removidos.
  
  #  Adicionar arquivos
    # git add .
      Prepara todas as alterações (arquivos modificados e novos) para serem incluídas no próximo commit. Você também pode adicionar arquivos individualmente: git add nome_do_arquivo.
  
  #  Criar um commit
    # git commit -m "Mensagem descritiva do commit"
      Cria um novo commit com as alterações preparadas. A mensagem do commit deve ser clara e concisa, descrevendo as alterações feitas.
  
  # Enviar para o repositório remoto
    # git push
      Envia os commits para o repositório remoto, disponibilizando suas alterações para outros colaboradores.
  
  # Atualizar o repositório local
    # git pull
      Baixa as alterações do repositório remoto e as mescla com o seu branch local, garantindo que você tenha a versão mais recente do código.
  
  #  Criar e trocar de branch
    # git branch <nome_do_branch>  
      Cria um novo branch
    # git checkout <nome_do_branch> # Troca para o branch especificado
      Branches permitem trabalhar em novas funcionalidades ou correções sem afetar o código principal.
  
  ##Mesclar branches
  # git merge <nome_do_branch>
    Mescla as alterações de um branch para outro (geralmente o branch principal).
  # git log
    Visualizar o histórico de commits

