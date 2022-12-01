# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```
---
➜ yarn run ts-node --files scripts/Deployment.ts "nuez" "fresa" "macadamia" "limon"
 - https://goerli.etherscan.io/tx/0xde1c52659c042d85b6a4efaa35bd875514bf05aa23cd72c0f0dc7691612cee32

- trying to vote without rights
yarn run ts-node --files scripts/extra_NoVote.ts 0x561CB9b1fbb98DbCB149D84DFf4F7B2B0465A4A5 0

➜ yarn run ts-node --files scripts/GiveRightToVote.ts 0x561CB9b1fbb98DbCB149D84DFf4F7B2B0465A4A5 0xcaff7bcD521B4f386a5AeBA144fAC4c587D7F706
yarn run ts-node --files scripts/GiveRightToVote.ts 0x561CB9b1fbb98DbCB149D84DFf4F7B2B0465A4A5 0xA5425ad28D844cD76C399D98878AA95002fC305d

yarn run ts-node --files scripts/GetChairperson.ts 0x561CB9b1fbb98DbCB149D84DFf4F7B2B0465A4A5


yarn run ts-node --files scripts/Vote.ts 0x47a93ffcc41ae14149d6cd5324d50664e866a821 1
    - chairperson voted https://goerli.etherscan.io/tx/0x9647dc179a4524beb25649c62241c241fd334dab69d4c524a21b0b14b15197e5


    --- delegate
    -- compi
    yarn run ts-node --files scripts/Delegate.ts 0x47a93ffcc41ae14149d6cd5324d50664e866a821 0xba102c751d6DC627f42A11Bc8c5f06a65a32b5D3


Get PRoposal
yarn run ts-node --files scripts/extra_GetProposal.ts 0x47a93ffcc41ae14149d6cd5324d50664e866a821 1



----
newest 

yarn run ts-node --files scripts/GiveVotingTokens.ts 0x2F78D7476869d3057ce137F8E38f3A8B24244C4E 0xba102c751d6DC627f42A11Bc8c5f06a65a32b5D3
yarn run ts-node --files scripts/GiveVotingTokens.ts 0x2F78D7476869d3057ce137F8E38f3A8B24244C4E 0xcaff7bcD521B4f386a5AeBA144fAC4c587D7F706

yarn run ts-node --files scripts/Selfdelegate.ts 0x80230c5f234ac2d4e734a724bDD4c9c0DbdC45D2 0
yarn run ts-node --files scripts/Vote.ts 0x80230c5f234ac2d4e734a724bDD4c9c0DbdC45D2 0