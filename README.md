# My_first_Hello_World_Smart_Contract


## 

1.  run the following command in the terminal.
    ```
    npm install --save-dev @nomiclabs/hardhat-ethers
    ```
    Hardhat ethers is a plugin that gives us access to ethers.js library. Ethers.js library gives us a way to interact with the blockchain world, we can deploy contracts, we can fetch contracts, we can call their functions

2. We are ready for deployment. Run the following command.
    ```
    npx hardhat run scripts/deploy.js --network goerli
    ```
     your contract will be deployed and you will be able to see the address of the contract on the terminal. 🔮🔮Copy that and save in your .env file with variable name as CONTRACT_ADDRESS, we will use it later to interact with the contract.

3. Now your .env file should look something like this
    ```
    PRIVATE_KEY = YOUR_PRIVATE_KEY
    API_URL_KEY = YOUR_API_URL_KEY
    API_KEY = YOUR_API_KEY
    CONTRACT_ADDRESS = YOUR_DEPLOYED_CONTRACT_ADDRESS
    ```
    
4. Run the following command again but this time, we will call the interact.js file.
    ```
    npx hardhat run scripts/interact.js --network goerli
    ```

5. You will see something like this.
    ```
    the message is Hello World! Bingo
    the new message is Good Bye, World!
    ```
    
    
