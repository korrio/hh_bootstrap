# Hardhat Bootstrap
DISCLAIMER: This project is for “Ethereum & ÐApps Development for DeFi” by AQ1.

## Set `hh` alias on `~/.zshrc` or `~/.bashrc`
- `alias hh="npx hardhat"`

## Installation
- `git clone https://github.com/korrio/hh-bootstrap.git`
- `cd hh-bootstrap`
- `yarn install`

## Requirements
- ERC20Token address (to deploy, run `hh deploy --tags YourTokenName`)
- Create `.secret` file and provide credential following

```
{
    "infuraProjectId": "",
    "alchemyProjectId": "",
    "privateKey": [
        DEPLOYER_PRIVATE_KEY,
        ],
    "etherApiKey": "",
    "bscApiKey": ""
}

```

# Deployment
- Run `hh deploy`