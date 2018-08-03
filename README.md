# AirDrop-Contract
多用户空投合约
1. Deploy both contract.
2. Token: approve
	_spender: airdrop contract address
	_value: # of token unit
3. AirDrop:
	from: holder/owner address
	caddress: token contract address
	_tos: ["0x...","0x..."] target address
	v: # of airdrop token
