# Commands

- git init -> inicia repositório git
- git clone 'link-repo-remoto' -> clona um projeto do repo remoto
- git remote -v -> lista o link de origem do repo remoto
- git remote add origin 'link-repo-remoto' -> adiciona uma origem ao repo local
- git config --list -> exibe configurações do git a nível de sistema, usuário e projeto
- git config --system --edit -> configurações git do sistema
- git config --global --edit -> configurações git do usuário
- git config --global core.editor code -> define o editor de configurações do git
- git config --edit -> configurações locais do projeto ou diretório atual
- git status -> mostra quais arquivos foram modificados e que estarão possivelmente no próximo commit
- git status -s -> && reduzido
- git add 'nome-arquivo' ou . -> tira os arquivos do untracked e coloca no stage area
- ***unstage area*** -> arquivos e não foram adicionados no git add, porém é reconhecido pelo git que já foi modificado
- para criar alias vá nas configurações globais e adicione uma seção [alias]
- git add . não adiciona os arquivos se for executado fora do níve de diretórios deles, para funcionar deve ser adicionado a flag --all