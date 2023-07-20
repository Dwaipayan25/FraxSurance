# FraxSurance

## Description:

1. The inspiration behind creating FraxShield, the Decentralised Insurance Platform, stems from a vision to bring transformative change to the insurance industry.
2. FRAX, as a stablecoin, played a pivotal role in shaping the concept of FraxShield. Its stability and peg to a value of 1 USD made it an ideal candidate to serve as the primary currency within the insurance ecosystem. Leveraging FRAX tokens allowed us to offer users the ability to lock their tokens, earning them valuable discounts on insurance premiums. Additionally, enabling customers to purchase insurance premiums in the form of NFTs using FRAX further enhanced the platform's versatility and ease of use.
3. FraxShield stands out with its inflation-protected insurance coverage. By using the stability of FRAX tokens, where 1FRAX equals 1 USD, and incorporating truflation data, we ensure policyholders' purchasing power is safeguarded against inflation's impact. This combination of FRAX and truflation sets FraxShield apart, providing customers with peace of mind and reliable financial security.

## Model:
<img width="1676" alt="Screenshot 2023-07-18 at 12 10 38 PM" src="https://github.com/Dwaipayan25/FraxSurance/assets/91361409/76c3bb2b-6418-4604-8d1a-11de2a8ed988">


### **Here are the key points highlighting what FraxShield does**

- FraxShield is a Decentralised Insurance Platform designed for the FraxBuild Hackathon.
- Users can lock Frax tokens, earning them discounts on insurance premiums as an incentive to participate.
- The platform allows users to purchase insurance premiums in the form of NFTs using FRAX tokens, a stablecoin with a 1:1 peg to the USD.
- When customers make insurance claims, the platform reviews and facilitates payment to the policy owner in FRAX tokens.
- FraxShield's unique feature is its inflation-protected insurance coverage, mitigating the risk of inflation eroding the policyholder's purchasing power.
- The insurance premium is calculated based on the inflation value of 1 USD, obtained using truflation, an off-chain mechanism tracking real-world inflation rates, the inflation data is regularly updated using chainlink automation.
- By leveraging the stability of FRAX tokens and incorporating truflation data, FraxShield ensures customers' assets are safeguarded against the impact of inflation, providing them with confidence and financial security.

Through this innovative blend of NFTs, FRAX , Truflation data, and ChainLink automation, FraxSurance crafts an insurance platform that harmonizes convenience, security,risk-free environment and inflation protection. By putting the power back into the hands of the users, this visionary project enculcates the spirit of technological advancement and a genuine commitment to empowering individuals and businesses in their pursuit of comprehensive insurance coverage.

## Installation:

1. Clone the FraxSurance repository
    
     `git clone https://github.com/Dwaipayan25/FraxSurance.git`
    
2. To deploy contract `cd smartContract`
3. run `npm install`
4. set up environment variables for [Private Key].
5. Connect your account to `goerli testnet` and `deploy`
6. run:
    1. `npx hardhat run scripts/deploy.js`
    2. `npx hardhat run scripts/fraxDeploy.js`
    3. `npx hardhat run scripts/truflationDeploy.js`
7. To run the project locally: go to `cd frontend`
8. Now the add the address of `NFT, Marketplace, FRAX and Truflation` at respective holders in `App.js`
9. Automate the `requestYoyInflation` function in Truflation.js using ChainLink. Example: https://automation.chain.link/goerli/85824714380130344892932313821863739689977789604226601839239682192663830603858
10. Install the necessary dependencies: `npm install`
11. Run the FraxShield `npm run start`

## Support

If you encounter any issues or have questions about `FraxSurance`, please reach out to me at my twitter handle https://twitter.com/dwaipayan01.
