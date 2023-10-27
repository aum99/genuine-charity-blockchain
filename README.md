


Create a Transparent Charity System using Smart Contracts on Ethereum.




## STATUS
- THIS PROJECT IS INCOMPLETE AND SHOULD ONLY BE USED FOR LOGICAL AND FUNDAMENTAL UNDERSTANDING PURPOSE.
- THE SOLIDITY CODE IS WRITTEN IN OLD VERSION SO REWRITING IT IN NEW VERSION IS RECOMMENDED.
- THE FRONTEND IS READY.
- THE SMART CONTRACT IS NOT CONNECTED TO THE REACT APP.
- THE SMART CONTRACT WORKS EXCEPT SOME LOGICAL ERRORS PROBABLY DUE TO THE ISSUES IN THE OLD VERSION USED TO BUILD THIS PROJECT
## Authors

- [@aum99](https://www.github.com/aum99)
- [@anjalikanki](https://www.github.com/anjalikanki)
- [@ujjwalpandey13](https://www.github.com/ujjwalpandey13)
- [@prasanna2609](https://www.github.com/prasanna2609)



## 🔗 The Design of Charity System Based on Blockchain

The charity system mode proposed is shown in the Figure below. There are four roles: donors, beneficiaries, charity organizations and cooperative stores. The charity organizations get the information of seek help and create charity projects through the platform. Donors learn about charity projects on the platform, then donate to beneficiaries or the charity organizations. Beneficiaries upload their information to the platform for help, they can get and spend tokens in cooperative stores. The transactions occurred in the stores will be uploaded to the charity platform. The cooperative stores supply services or goods to the beneficiaries to obtain tokens. The tokens can be exchanged for real money by charity organizations.The flow of funds has been fully recorded on the blockchain, which allows transactions to be tracked and funds prevented from being abused.
## Platform Usage Process

1. Donor After successful login, the donor browses the charity projects and select one project to be donated. The system will check the balance of donor account. If the balance is insufficient, the user will be reminded to deposit.Donation can be completed only the balance is sufficient.
2. People in need The people who need help should fill in the rescue information which will be uploaded to the charity organization for review, and the approved projects will be posted on the charity platform. The beneficiary can check the account balance to know the project status, and then use the tokens in cooperative shops to obtain services or products.
3. Cooperative shops The shops provides the corresponding services or goods such as medicines or books to the beneficiaries to obtain tokens.they can exchange tokens for real money by charity organizations.
1. Charity organization The organization can get donation from the platform to help other people and apply money to the cooperative shops for token exchanging
## Dapp Model

Following functions have been met:

1. Beneficiary initiates a charity project in the DApp.
2. Beneficiary requests funds from the charity project initiated by himself.
3. Donor donates to the charity projects which he chooses.
4. Donor is able to vote on the funding request for the charity project already participated.
5. After the request for funds is approved, the funds are automatically transferred to the beneficiary's account.
## Description
- We have created a Solidity Smart Contract for this cause and we have used web3, ganache-cli, mocha, to test out our contract.

- In the contracts folder, you will find a final solidity contract and the individual modules inside contracts_classified directory.

- On the Frontend Part we have html,css,javascript and full UI of Genuine Charity App along with Admin Panel in the website folder.

- Included a test directory with a test file to test all the functions used in the contract by deploying it on ganache and using web3 to utilize the ABI.

- Included a sample React Template so that the frontend can be used to include the website along with the test code to make a production app.

- Included code to compile the contract and to deploy the contract on the Rinkeby Test Network using the Infuria node module.

- The website and the test modules are not yet connected and the code is placed in seperate folders.

## Tech Stack

Tools and technologies that we learnt and used in the project.

- Solidity
- HTML,CSS,JS,React
- Node JS
- web3,ganache-cli,mocha,solc node modules