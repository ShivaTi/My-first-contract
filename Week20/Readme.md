## Deploy the contracts to a live Testnet

Contracts in this exercise are tested  on MetaMask to the Ropsten  network.

After switching MetaMask to Ropsten Network, deploy the contracts as before and copy/keep a note of their deployed addresses. 
To deploy ::
1. AssociateProfitSplitter use 0x9eCA6401bD478F3bE1f111C950640aD5ef8150C0 as contract addresss

2. TiredProfitSplitter use  0x3e1844b29060298Bcca88ca0FABd6BA7c2027c26 as contract address

3. and finally for DeferredEquityPlan use 0xfF7216cD31b8d81773e91163719E57Dc4a6Fc13B  as contract address

## Level One : The AssociateProfitSplitter

This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

`AssociateProfitSplitter` - Contract Deployment link 0x9eCA6401bD478F3bE1f111C950640aD5ef8150C0



![Screenshot (616)](https://user-images.githubusercontent.com/73386878/114268753-2be8d700-9a46-11eb-8faf-97ca9be24af2.png)


![Screenshot (617)](https://user-images.githubusercontent.com/73386878/114268756-3014f480-9a46-11eb-821b-1a64b97e7bcb.png)






## levelTwo : TieredProfitSplitter Contract

In this contract, rather than splitting the profits between Associate-level employees, it is calculated by rudimentary percentages for different tiers of employees (CEO, CTO, and Bob).

`TieredProfitSplitter` - Contract Deployment link 0x3e1844b29060298Bcca88ca0FABd6BA7c2027c26

![Screenshot (619)](https://user-images.githubusercontent.com/73386878/114268795-62265680-9a46-11eb-9682-2932405e5868.png)

![Screenshot (620)](https://user-images.githubusercontent.com/73386878/114268797-63f01a00-9a46-11eb-8e61-0481d6ce0416.png)


## LevelThree : DeferredEquityPlan Contract

In this contract, we are managing an employee's "deferred equity incentive plan" in which 1000 shares will be distributed over 4 years to the employee. We won't need to work with Ether in this contract, but we will be storing and setting amounts that represent the number of distributed shares the employee owns and enforcing the vetting periods automatically.

`DeferredEquityPlan` Contract Deployment  use 0xfF7216cD31b8d81773e91163719E57Dc4a6Fc13B

regarding fastforward function , it helps to precalcuate the share allocation by the help of fakenow timing.

