# comandos linux, git, github e postgresql mais utilizados

## linux

### navegação e manipulação de arquivos

  * `ls`: listar arquivos e diretórios.
  * `cd`: mudar de diretório.
  * `pwd`: exibir o diretório atual.
  * `mkdir`: criar diretório.
  * `rmdir`: remover diretório vazio.
  * `touch`: criar arquivo vazio.
  * `cp`: copiar arquivo ou diretório.
  * `mv`: mover ou renomear arquivo/diretório.
  * `rm`: remover arquivo.
  * `rm -r`: remover diretório e seu conteúdo.
  * `cat`: exibir conteúdo de arquivo.
  * `less`: visualizar arquivo grande (navegação interativa).
  * `head`: exibir início do arquivo.
  * `tail`: exibir final do arquivo.
  * `tail -f`: seguir novas linhas adicionadas a um arquivo.
  * `grep`: pesquisar padrões em arquivos.
  * `find`: localizar arquivos/diretórios.
  * `which`: localizar binário executável.
  * `whereis`: localizar binário, fonte e manual.
  * `locate`: localizar arquivos (base de dados atualizada com updatedb).

### permissões e usuários

  * `chmod`: alterar permissões de arquivo/diretório.
  * `chown`: alterar proprietário.
  * `chgrp`: alterar grupo.
  * `useradd`: criar usuário.
  * `userdel`: remover usuário.
  * `passwd`: alterar senha de usuário.
  * `sudo`: executar comando como administrador.
  * `su`: trocar para usuário diferente.

### processos e gerenciamento

  * `ps`: exibir processos em execução.
  * `top`: monitorar processos em tempo real.
  * `htop`: versão interativa do top.
  * `kill`: encerrar processo.
  * `kill -9`: encerrar processo forçosamente.
  * `pkill`: encerrar processo pelo nome.
  * `bg`: mover processo para background.
  * `fg`: trazer processo para foreground.
  * `jobs`: listar processos em background.

### rede

  * `ifconfig`: configurar interface de rede (deprecated, use ip).
  * `ip addr`: exibir configurções de interface.
  * `ip link`: gerenciar interfaces.
  * `ping`: testar conectividade.
  * `ssh`: conectar-se a servidor remoto.
  * `scp`: copiar arquivos via ssh.
  * `rsync`: sincronizar arquivos/diretórios.
  * `netstat`: exibir informações de rede.
  * `curl`: transferir dados de/para servidor.
  * `wget`: baixar arquivos de rede.

### pacotes e instalação

  * `apt-get`: gerenciar pacotes debian/ubuntu.
  * `yum`: gerenciar pacotes centos/rhel.
  * `dnf`: gerenciar pacotes fedora.
  * `rpm`: instalar/remover pacotes rpm.
  * `dpkg`: instalar/remover pacotes deb.
  * `tar`: manipular arquivos tar.
  * `gzip`: comprimir/decomprimir arquivos gzip.
  * `bzip2`: comprimir/decomprimir arquivos bzip2.
  * `unzip`: extrair arquivos zip.

### outros

  * `history`: exibir histórico de comandos.
  * `alias`: criar atalhos para comandos.
  * `man`: exibir manual de comando.
  * `info`: exibir informações detalhadas (alternativa ao man).
  * `clear`: limpar tela.
  * `exit`: sair do shell.
  * `shutdown`: desligar/reiniciar o sistema.
  * `reboot`: reiniciar o sistema.
  * `cron`: agendar tarefas (crontab -e para editar).
  * `systemctl`: gerenciar serviços systemd.
  * `journalctl`: exibir logs do sistema.

## git

### configuração básica

  * `git config --global user.name "nome"`: define o nome do usuário.
  * `git config --global user.email "email"`: define o email do usuário.
  * `git config --global core.editor "editor"`: define o editor de texto padrão.

### repositório local

  * `git init`: inicializa um novo repositório.
  * `git clone <url>`: clona um repositório remoto.
  * `git add <arquivo>`: adiciona arquivo para staged.
  * `git add .`: adiciona todos os arquivos modificados para staged.
  * `git commit -m "mensagem"`: commita as alterações.
  * `git status`: exibe o status do repositório.
  * `git log`: exibe histórico de commits.
  * `git diff`: exibe diferenças entre commits.
  * `git branch`: lista branches.
  * `git branch <nome>`: cria um novo branch.
  * `git checkout <branch>`: muda para branch.
  * `git checkout -b <nome>`: cria e muda para branch.
  * `git merge <branch>`: merge branch atual com o especificado.
  * `git rebase <branch>`: rebase branch atual no especificado.
  * `git reset --hard <commit>`: descarta alterações e volta para commit.
  * `git checkout -- <arquivo>`: descarta alterações em arquivo.

### repositório remoto

  * `git remote add <nome> <url>`: adiciona um repositório remoto.
  * `git remote -v`: exibe repositórios remotos.
  * `git pull <remoto> <branch>`: atualiza repositório local.
  * `git push <remoto> <branch>`: envia alterações para repositório remoto.
  * `git fetch <remoto>`: baixa objetos de repositório remoto (sem merge).
  * `git remote remove <nome>`: remove repositório remoto.
  * `git remote rename <antigo> <novo>`: renomeia repositório remoto.

### colaboração

  * `git fetch upstream`: baixa alterações do repositório upstream.
  * `git merge upstream/main`: merge branch principal upstream.
  * `git rebase upstream/main`: rebase no branch principal upstream.
  * `git pull request`: comando para criar pull request (no github).
  * `git review`: comando para enviar revisão (no git review).

## github

### configuração e autenticação

  * `git remote add origin <url>`: adiciona repositório do github.
  * `gh auth login`: autentica com github usando cli do github.
  * `gh repo clone <usuario/repo>`: clona repositório usando cli do github.

### gerenciamento de repositórios

  * `gh repo create <nome>`: cria um novo repositório no github.
  * `gh repo delete <usuario/repo>`: exclui repositório do github.
  * `gh repo fork <usuario/repo>`: fork repositório usando cli do github.
  * `gh repo list <usuario>`: lista repositórios de um usuário.
  * `gh repo view <usuario/repo>`: exibe informações de um repositório.

### pull requests e issues

  * `gh pr create`: cria um pull request.
  * `gh pr list`: lista pull requests do repositório.
  * `gh pr view <numero>`: exibe detalhes de um pull request.
  * `gh pr merge <numero>`: merge um pull request.
  * `gh pr close <numero>`: fecha um pull request.
  * `gh issue create`: cria uma issue.
  * `gh issue list`: lista issues do repositório.
  * `gh issue view <numero>`: exibe detalhes de uma issue.
  * `gh issue edit <numero>`: edita uma issue.
  * `gh issue close <numero>`: fecha uma issue.

### colaboração

  * `gh repo share <usuario/repo>`: compartilha repositório com equipe/organização.
  * `gh collaboration add <usuario> --repo <usuario/repo>`: adiciona colaborador.
  * `gh collaboration remove <usuario> --repo <usuario/repo>`: remove colaborador.

## postgresql

### banco de dados

  * `psql -U usuario -d banco`: conecta-se ao banco de dados.
  * `\q`: sai do psql.
  * `\list`: lista bancos de dados.
  * `\c [banco]`: conecta-se a um banco de dados.
  * `CREATE DATABASE nome;`: cria um novo banco de dados.
  * `DROP DATABASE nome;`: remove um banco de dados.
  * `\connect banco`: conectar-se a outro banco de dados.

### tabelas e esquemas

  * `CREATE TABLE tabela (coluna tipo, ...);`: cria tabela.
  * `DROP TABLE tabela;`: remove tabela.
  * `\d`: lista tabelas.
  * `\d tabela`: exibe estrutura da tabela.
  * `ALTER TABLE tabela ADD COLUMN coluna tipo;`: adiciona coluna.
  * `ALTER TABLE tabela DROP COLUMN coluna;`: remove coluna.
  * `ALTER TABLE tabela RENAME COLUMN antigo TO novo;`: renomeia coluna.
  * `CREATE INDEX indice ON tabela (coluna);`: cria índice.
  * `DROP INDEX indice;`: remove índice.

### consultas e dados

  * `SELECT * FROM tabela;`: seleciona todos os registros.
  * `SELECT coluna FROM tabela WHERE condicao;`: seleciona com condição.
  * `INSERT INTO tabela (coluna, ...) VALUES (valor, ...);`: insere registro.
  * `UPDATE tabela SET coluna = valor WHERE condicao;`: atualiza registro.
  * `DELETE FROM tabela WHERE condicao;`: deleta registro.
  * `TRUNCATE TABLE tabela;`: remove todos os registros da tabela.
  * `ALTER SEQUENCE tabela_id_seq RESTART WITH valor;`: redefine sequência de id.
  * `COPY tabela TO 'arquivo.csv' DELIMITER ',' CSV HEADER;`: exporta tabela para csv.
  * `COPY tabela FROM 'arquivo.csv' DELIMITER ',' CSV HEADER;`: importa tabela de csv.

### usuários e permissões

  * `CREATE USER usuario WITH PASSWORD 'senha';`: cria usuário.
  * `DROP USER usuario;`: remove usuário.
  * `ALTER USER usuario RENAME TO novo_usuario;`: renomeia usuário.
  * `ALTER USER usuario WITH PASSWORD 'nova_senha';`: altera senha.
  * `GRANT SELECT ON tabela TO usuario;`: concede permissão.
  * `REVOKE SELECT ON tabela FROM usuario;`: revoga permissão.
  * `\du`: lista usuários e funções.

### funções e Stored Procedures

  * `CREATE FUNCTION nome() RETURNS tipo AS $$ ... $$ LANGUAGE plpgsql;`: cria função.
  * `DROP FUNCTION nome();`: remove função.
  * `CREATE OR REPLACE FUNCTION nome() RETURNS tipo AS $$ ... $$ LANGUAGE plpgsql;`: substitui função existente.
  * `CREATE PROCEDURE nome() AS $$ ... $$ LANGUAGE plpgsql;`: cria procedure.
  * `CALL nome();`: chama procedure.

### backup e restauração

  * `pg_dump banco > backup.sql`: cria backup do banco de dados.
  * `psql -d banco -f backup.sql`: restaura backup.
  * `pg_dumpall > backupall.sql`: backup de todos os bancos e configurações de usuário.
  * `pg_restore -d banco backup.tar`: restaura backup de dump binário.
  * `pg_basebackup -D /backup/diretorio`: backup físico do cluster.

### administração e monitoramento

  * `\dt`: lista tabelas.
  * `\dv`: lista views.
  * `\ds`: lista sequências.
  * `\df`: lista funções.
  * `\du`: lista usuários e funções.
  * `\dp`: lista permissões.
  * `\l`: lista bancos de dados.
  * `\conninfo`: exibe informações de conexão.
  * `SHOW all;`: exibe configurações atuais.
  * `EXPLAIN SELECT * FROM tabela;`: exibe plano de execução da consulta.
  * `VACUUM;`: limpa tabela e otimiza armazenamento.
  * `ANALYZE;`: atualiza estatísticas do banco de dados.