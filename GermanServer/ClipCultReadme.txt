ClipCult


Ferramentas:


Flask: Flask é um microframework em Python baseado em Werkzeug e Jinja 2. Ele é licenciado pela Licença BSD. Você pode baixar pelo PIP (preferencia) ou você pode encontrar Flask em:
* http://flask.pocoo.org/
Bons tutoriais de Flask:
        -http://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask
        -http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world


SQLAlchemy: O SQLAlchemy é uma ferramenta que cria uma layer fácil de operar para bancos de dados baseados em SQL. Você pode baixar pelo PIP (preferencia) ou você encontra o SQLAlchemy em http://www.sqlalchemy.org/
O SQLAlchemy funciona com o flask usando uma pequena interface chamada Flask-SQLAlchemy:
-http://flask.pocoo.org/docs/0.10/patterns/sqlalchemy/


SQLite: O SQLite é uma database minimalista para SQL. Você pode encontrá-la em https://www.sqlite.org/ Você precisa saber SQL para alterar as tabelas.


Flask-Bootstrap: É uma outra extensão do Flask, essa usada para servir páginas em bootstrap. Todas as páginas ficam em templates e todos os arquivos, referências, imagens tem que ficar em static. Lembre-se de ajustar os caminhos em suas páginas para levar isso em consideração. Você pode baixar pelo PIP.


Tornado Server: Flask sozinho é péssimo pra se dar com multiplas requisições. Para isso, colocamos ele dentro de um container. No caso o escolhido foi o tornado. Você pode encontrar o Tornado no PIP e você vê como faz a integração aqui:
-http://flask.pocoo.org/docs/0.10/deploying/wsgi-standalone/


Empório:


O empório atualmente é uma web page estática hospedada no servidor. Para colocar ou retirar produtos, é preciso modificar a página para que ela aponte para os novos espaços. A sugestão é mudar o empório para uma loja Wix:
        -http://pt.wix.com/ecommerce/website


Tarefas à realizar:
-Adicionar um sistema de avaliação de vídeos.
-Aumentar opções de procura de vídeos (por nome de usuário, data de publicação e por ranking).
-Ranquear um vídeo publicado.
-Migrar o BD para um outro mais robusto(MYSQL ou Postgree)
-As tabelas base na pasta raiz já foram alteradas para aceitar rankeamento e notas.