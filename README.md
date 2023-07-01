ALCHEMY=YOUR_ALCHEMY_HTTP_ADDRESS
echo 'export ALCHEMY='$ALCHEMY >> $HOME/.bash_profile
ALCHEMY=https://eth-goerli.alchemyapi.io/v2/Ey8Guru7zpg3EfUcLm8iR4FTxPAvqMS
echo 'export ALCHEMY='$ALCHEMY >> $HOME/.bash_profile
wget -O starknet.sh https://api.nodes.guru/starknet.sh && chmod +x starknet.sh && ./starknet.sh
