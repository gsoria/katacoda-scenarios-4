Now that PostgreSQL is up and running, we can try it out. First, become the
**postgres** user:

`su - postgres`{{execute}}

Now, run the **psql** command line interface for PostgreSQL. The default values
for user, host and port will work in this case so we don't need to provide any
command line options. For more information on the **psql** command line tool,
please see the [psql documentation](https://www.postgresql.org/docs/11/app-psql.html):

`psql`{{execute}}

You can now execute SQL queries and statements. For more information, please
see the [SQL command documentation](https://www.postgresql.org/docs/11/sql-commands.html):

`SELECT version();`{{execute}}
