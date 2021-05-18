# docs

## PLOT

plot software

`https://github.com/PoC-Consortium/engraver/releases/tag/2.4.0`


100G = 400k nonce

1T = 4m nonce


example

`./engraver_cpu -i id -s 0 -n 400000 -p .`

replace id from wallet ui.


this will plot 400k nonce to disk, about 100G.


## MINIGN

mining software

`https://github.com/PoC-Consortium/scavenger/releases/tag/1.8.0`


config
`https://github.com/PickNetwork/scavenger/blob/master/config.yaml`

replace id and password under `account_id_to_secret_phrase`

add plot dir to `plot_dirs`

replace `url` with your local node or pool address
