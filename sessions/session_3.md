# session 3 of building The Joy in the open

## trivial things that make all the difference

On developing a new application, in my case a portfolios manager in the context of position/swing/intraday training, u need to kill a db several times in a row until you're absolutely sure of your first database schema migration, this means I had to take time plugging in a DBeaver instance to the DB in my bare metal server via SSH. SPOILER ALERT: too much overhead, I renounced, I'd rather run manual queries in the CLI on the server itself. Lesson learned (again): be mindful what you ship modafucka.