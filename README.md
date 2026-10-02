# AI trading game: agent settings

One file, `agents.json`: the owner's changes to each agent's surprise threshold (1% to 10%) plus a history of changes.
It is written by the game's dashboard and read by the scheduled game routines at the start of each pass.
It holds no secrets. If this repo cannot be reached the game uses the defaults in its own `config/live.toml`.
