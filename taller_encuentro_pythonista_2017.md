Taller SQLAlchemy
======================
- Presentacion
  * que es un ORM
  * que es SQLAlchemy
  * no con NoSQL
- Taller (con BD sqlite)
  * instalacion (virtualenv/pip install)
    instalar virtualenv:
      - sudo pip install virtualenv (o con la paqueteria de su distribucion, si es windows seguir http://www.tylerbutler.com/2012/05/how-to-install-python-pip-and-virtualenv-on-windows-with-powershell/)
      - virtualenv -p python3 taller_sqlalchemy
      - cd taller_sqlalchemy
      - source bin/activate
      - pip install sqlalchemy
      - MySQL: pip install mysqlclient pymysql
      - PostgreSQL: pip install psycopg2
  * mostrar esquema
  * seguir el tutorial de SQLAlchemy de mi notebook
    + algunas cosas quedan fuera
    + se agrega @property
  * demostrar conexion con otro motor (mysql: pip install mysqlclient)
- De la mano con Conceptos?
  * DBAPI (pep 249)
  * engine, connection pools, dialects
  * SQLAlchemy Core vs SQLAlchemy ORM
  * Tipos de datos
  * Sesiones (session factory -> sessions)
  * Algunas operaciones en un query (all, one, count, filter, distinct, join, limit, order_by, ...)
  * Relaciones soportadas (uno-muchos, muchos-uno, uno-uno, muchos-muchos)
- Links relevantes
  * SQLAlchemy docs http://docs.sqlalchemy.org/en/rel_1_1/
  * SQLAlchemy tutorial http://docs.sqlalchemy.org/en/rel_1_1/orm/tutorial.html
  * Otro tuto https://auth0.com/blog/sqlalchemy-orm-tutorial-for-python-developers/
