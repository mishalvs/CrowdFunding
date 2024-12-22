# Crowd funding

### Project features :bulb:

- [x] User can start a fundraising.
- [x] Anyone can contribute.
- [x] End project if targeted contribution amount reached.
- [x] Expire project if targeted amount not fulfills between deadline.
- [x] Contributors can withdraw contributed amount if project expire.
- [x] Owner need to request contributors for withdraw amount.
- [x] Owner can withdraw amount if 50% contributors agree.
- [x] Connect with waller.

### How to run :runner: :

- Run hardhat node
    ```
    npx hardhat node
    ```
- Run test cases
    ```
    npx hardhat test
    ```
- Connect HardHat Account to Metamask


- Deploy contract in local hardhat node
    ```
    npx hardhat run scripts/deploy.js --network localhost
    ```
- Run Next.js frontend
    ```
    cd client
    npm run dev
    ```
- Connect account to  website


### Hardhat commands
```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/deploy.js
npx hardhat help
npx hardhat run scripts/deploy.js --network <network name>
```
