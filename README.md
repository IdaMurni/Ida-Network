# Ida-Network

<p align="center">
  <img src="https://github.com/IdaMurni/website/blob/main/src/assets/img/ida_murni_master.png" width="200"/>
</p>

<p align="center">This Repo represent of PoA consensus of IdaMurni Network</p>

the Cities represent of the nodes that contains of ida.json as a genesis file that run in the same chainId from deference ports.

default ChainId: 10587

to run the project on each nodes
```shell
geth --datadir <city>/ --syncmode 'full' --port 30310 --http.addr="localhost" --http.port="1337" --http.api="admin,debug,web3,eth,txpool,personal,miner,net" --bootnodes 'enode://7ceef7a86aa4a552c8e767968758da9959815691287329aa0eb55ac05fea06b829f63e1bf2dc34d90eb28943f8d20a0071847457f85f9fe4ada96839f09bbbb1@127.0.0.1:0?discport=30310' --networkid 10587 --unlock <'city_address'> --password <city>/password.txt --mine
```