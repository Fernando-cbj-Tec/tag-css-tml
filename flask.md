## flask

### aplicação básica

  * `Flask()`: cria uma instância do aplicativo flask.
  * `app.route()`: decoraador para associar uma função a uma url.
  * `render_template()`: renderiza um template.
  * `request`: objeto que contém os dados da requisição.
  * `redirect()`: redireciona o usuário para outra url.
  * `url_for()`: gera a url para uma função de visualização.
  * `flash()`: envia uma mensagem para a próxima solicitação.
  * `session`: objeto para armazenar dados entre solicitações.
  * `g`: objeto para variáveis globais do contexto da aplicação.
  * `app.config()`: configura variáveis de configuração da aplicação.

### bancos de dados

  * `SQLAlchemy()`: cria uma instância do orm sqlalchemy.
  * `db.create_all()`: cria todas as tabelas no banco de dados.
  * `db.session.add()`: adiciona um objeto ao banco de dados.
  * `db.session.commit()`: salva as alterações no banco de dados.
  * `db.session.rollback()`: desfaz as alterações não salvas.
  * `db.session.delete()`: remove um objeto do banco de dados.
  * `query.all()`: retorna todos os resultados da consulta.
  * `query.filter_by()`: filtrar resultados com base em critérios.
  * `query.get()`: obtém um objeto pelo id.
  * `query.first()`: retorna o primeiro resultado da consulta.

### autenticação

  * `LoginManager()`: gerencia o login do usuário.
  * `login_user()`: registra o usuário como logado.
  * `logout_user()`: desloga o usuário.
  * `login_required`: decoraador para proteger rotas.
  * `current_user`: objeto que representa o usuário atualmente logado.
  * `UserMixin`: classe base para objetos de usuário.
  * `user_loader()`: carrega o usuário pelo id.
