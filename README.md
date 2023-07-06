Welcome to your new dbt project!

### Using the starter project

#### Start postgres server on brew
- `brew services start postgresql`
  - `brew services` should show the name of the server with status **started** 

#### Try running the following commands:
Go into dbt_playground folder and try running:
- `dbt run`
- `dbt test`


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](https://community.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices

### POSTGRES DB USED
- World from [postgresql.org](https://www.postgresql.org/ftp/projects/pgFoundry/dbsamples/world/world-1.0/)
- To load it, connect to postgres using

```psql -d <name_of_database>```
- Load it from 

```\i <path_to_file>/world.sql```