# Paylona – React SDK for Solana Pay

PAYLONA is an open-source React SDK that provides plug-and-play components and hooks for integrating **Solana Pay** into modern web applications.

Whether you're building a checkout page, a peer-to-peer payment app, or a crypto donation portal, Paylona makes it easier and faster to implement seamless, secure transactions using the Solana blockchain.

 Features

- React Components– Drop-in components like `<PayButton />`, `<TransactionStatusCard />`, and `<QRCodeDisplay />`.
- Custom Hooks– Use `useSolanaPay()` to handle payment logic and wallet interaction easily.
- QR Code Support – Generate and scan payment QR codes effortlessly.
- Solana Pay Protocol– Built on top of the official `@solana/pay` SDK.
- Naira-friendly Display – Optional currency conversion for Nigerian users.
-  Tailwind Styled – Clean, modern UI with Tailwind CSS support.

---

 Installation (coming soon)

bash
npm install paylona
# or
yarn add paylona


import { PayButton } from 'paylona';

<PayButton
  recipient="YourWalletAddressHere"
  amount={0.5}
  label="Pay Now"
/>

📁 Demo Project

Check the /example folder for a full working demo using Vite + React.


🛠 Tech Stack

React

Solana Pay (@solana/pay)

Tailwind CSS

Vite (for the example/demo)

Roadmap

[ ] Publish to npm

[ ] Add Storybook for live docs

[ ] Add currency plugin for NGN/SOL rates

[ ] Mobile optimization

[ ] React Native wrapper (experimental)

👥 Contributors

Built by Feranmi Ayoola
Gratefully supported by the Superteam Nigeria x Solana Foundation Grant

📄 License

MIT – Free to use, contribute, and build on 
