# HelloWorldContract
Blockgames internship first task.

This project is my blockgames internship first task.
Blockgames is hosted by Zuri Team in Collabration with Nestcoin

Contract Address: 0xFB4180701388537b6b8C6dF978d13BBBA3FC8052
https://rinkeby.etherscan.io/address/0xfb4180701388537b6b8c6df978d13bbba3fc8052#code

### Running locally

To run the app locally, follow the steps below:

1. Clone the repository to your PC using your terminal. For more info, refer to this [article](https://support.atlassian.com/bitbucket-cloud/docs/clone-a-repository/)

2. After cloning, navigate into the repo using:

   ```
   cd HelloWorldContract
   ```

3. Install the dependencies in the package.json using the command:

   ```
   npm install
   ```

4. After the dependencies have been installed successfully, create a .env file at the root. Take a look at the env.sample file and configure your environment variables with your values in the .env file.


5. After adding the environment variables,to deploy the smart contract in your terminal using the command:
   ```
   npx hardhat run scripts/deploy.js
   ```