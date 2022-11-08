# Contract Deployement using Quicknode

Project contains NFT contract designed from Openzeppelin Wizard. More and less, initial config. for deployement of contract using Quick Node. 


## Contract Address (Goerli):

`0x3075A0D04DC4C1E83d5f810b9E83cdBa2204E281`


## Tech Stack

[Quicknode](https://www.quicknode.com/)

[Openzeppelin](https://docs.openzeppelin.com/contracts/4.x/wizard)


## Lessons Learned

- Working with node modules (installations / intractions)
- Openzeppelin Wizard
- QuickNode
- Hardhat Basics


## Run Locally

Clone the project

```bash
  git clone https://github.com/hammadsaedi/QuickNode-Contract-Deployment
```

Go to the project directory

```bash
  cd QuickNode-Contract-Deployment
```

Install dependencies

```bash
  npm init --yes
  npm install --save-dev hardhat
  npm install @openzeppelin/contracts
  npm install dotenv
```

Compile contract

```bash
  npx hardhat compile
```



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"`

`PRIVATE_KEY="add-the-private-key-here"`



## Deployment

To deploy this project run

```bash
  npx hardhat run scripts/deploy.js --network goerli
```



## Authors

- [@hammadsaedi](https://www.github.com/hammadsaedi)



## License

[MIT](https://choosealicense.com/licenses/mit/)




## Acknowledgements

 - [Learn Web3 Dao](https://learnweb3.io/courses/9a3fafe4-b5eb-4329-bdef-97b2aa6aacc1/lessons/017e65bf-2a86-455e-a499-09b61ffa5241)
 - [Openzeppelin Wizard](https://docs.openzeppelin.com/contracts/4.x/wizard)
 - [Readme.so](https://readme.so/editor)



## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Feedback

If you have any feedback, please reach out to us at twitter [@hammadsaedi](https://twitter.com/hammadsaedi)
