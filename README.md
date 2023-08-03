<div style="text-align: center;">
     <img src="https://github.com/amilali/CrowdXfund/blob/main/img/circular%20dp.png" width="100px">

  <img src="https://github.com/amilali/CrowdXfund/blob/main/img/black_logo.jpg" alt="CrowdXfund" style="border-radius: 50%;" width="700px">                                  
</div>

CrowdXfund is a revolutionary blockchain-based crowdfunding decentralized application (DApp) that empowers individuals and organizations to launch, manage, and participate in crowdfunding campaigns with unprecedented security, transparency, and efficiency.



## Problem Statement and Necessity 
Crowdfunding is one of the most popular ways to raise funds for any project, cause or for helping any individual in need. With the onset of Covid we have seen a rise in Crowdfunding activities across the globe which includes small campaigns to help people get oxygen and medical help to large funds such as PM Cares.

The major problems with the Current Crowdfunding Platforms that we wanted to solve were : 
- Security : As the funds become larger, they need to be heavily secure, although stringent measures such as symmetric encryption are in place to make e-payment safe and secure,it is still vulnerable to hacking. Blockchain — which has never been compromised yet — can provide that level of security.
- Transparency and Anti-Fraud  : We have seen, and continue to see a lot of crowdfunding scams happening around. There is no way to see where the funds are being used. We wanted to make the entire flow of funds transparent at every stage, so that there is no possibility of the money being misused.
- Global contribution : With some of the platforms being country specific, it becomes hard for people from other countries to contribute to various campaigns. Using blockchain anyone in the world can contribute to the campaign. Transactions are quick and convenient.

We were highly inspired by the CryptoRelief initiative ([www.cryptorelief.in](https://www.cryptorelief.in))  which raised ~1 billion dollars for Covid Relief in India from the entire global community, in a highly transparent manner. 

## Detailed Report and PPT
- A Detailed Report of the Project can be [found here](https://docs.google.com/#)
- A Presentation on the Application can be [found here](https://docs.google.com/#)

## Screenshots 
#### Home Page :
![image](#)
### Campaign Page :
![image](#)
### Create Campaign Page :
![image](#)
### Withdrawal Request Page :
![image](#)
### New Withdrawal Request Page :
![image](#)



## Tech Stack 
- Next JS
- Chakra UI
- Solidity
- Web3.js
- Polygon (Matic)
- infura
- Hardhat

## To run the application locally
- Fork & clone the Project 
- run `npm install` to install all the dependencies
- run `npm run dev` to run the application locally

## Prerequisites to create Campaign and Contribute
1. Install **Metamask** as Google Chrome Extension and Create an account.
2.  Request Ether by sharing your ethereum address in social media <br>(`https://faucet.rinkeby.io/)`
3. Get 0.01 ether free by giving the ethereum address <br>`(http://rinkeby-faucet.com/)`

## To Deploy your own Contract 
1. Create an account in [https://infura.io](https://infura.io/)
2. Create .env file  and add these line to it.
	> NEXT_PUBLIC_RPC_URL=
     NEXT_PUBLIC_PRIVATE_KEY=
     NEXT_PUBLIC_ADDRESS=
     NEXT_PUBLIC_IPFS_ID=
     NEXT_PUBLIC_IPFS_KEY= '
3. Do the Changes that you want to do inside the Solidity File
4. Compile the Contract 
  `node compile.js`
5. Deploy Contract by going into smart-contract Directory and run.
	`node deploy.js`
	
   Copy the contract deploy address and replace it in factory.js file.
  
  
6. Replace your "infura end point link" in web3.js file


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Getting Started

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
