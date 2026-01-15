# Laravel Crypto Payment System

A **production-ready demo** showing how to accept and manage **crypto payments** using **Laravel**. Built to demonstrate real-world payment workflows for businesses, SaaS products, and Web3 platforms.


##  What This Project Does
This project allows users to:
- Enter a payment amount or units
- Automatically calculate crypto value
- Connect their wallet
- Send payment
- Verify the transaction
- Store payment records in the database

Admins can view all transactions from a secure dashboard.



##  Business Use Cases
- Crypto checkout systems
- Token sales & presales
- SaaS subscription payments
- Web3 applications
- Custom client payment solutions



##  Features
- Laravel backend architecture
- Crypto payment calculation
- Wallet connection support
- Transaction hash verification
- Secure database logging
- Admin dashboard for payments



##  Tech Stack
- **Backend:** Laravel, PHP
- **Frontend:** HTML, CSS, JavaScript
- **Blockchain:** BNB Chain, Solana
- **Wallets:** MetaMask, Trust Wallet, Phantom
- **Database:** MySQL



##  Project Structure
```text
app/
├── Http/
│ ├── Controllers/
│ │ ├── PaymentController.php
│ │ └── Admin/TransactionController.php
│ ├── Requests/
│ │ └── StoreTransactionRequest.php
├── Models/
│ └── Transaction.php
├── Services/
│ ├── CryptoPriceService.php
│ ├── BnbPaymentService.php
│ └── SolanaPaymentService.php


resources/
├── views/
│ ├── payment/
│ │ └── checkout.blade.php
│ └── admin/
│ └── transactions.blade.php
├── js/
│ ├── bnb-wallet.js
│ └── solana-wallet.js


routes/
├── web.php
└── api.php
````



##  Installation

```bash
git clone https://github.com/Frank56377/laravel-crypto-payment-system.git
cd laravel-crypto-payment-system
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```



##  Security Notes

* No private keys are stored
* Wallet-based transactions only
* Server-side validation enabled

## System Flow

User
  ↓
Payment Form (Units / Amount)
  ↓
Frontend Validation
  ↓
Wallet Connection (MetaMask / Phantom)
  ↓
Blockchain Transaction (BNB / Solana)
  ↓
Server-side Verification (Laravel)
  ↓
Database Logging (MySQL)
  ↓
Admin Dashboard (View & Manage Transactions)

This flow demonstrates a real-world crypto payment lifecycle, focusing on security, verification, and backend reliability.

##  Roadmap

* Live price conversion
* Multiple token support
* Webhook confirmations
* Export transactions



If you need a **custom crypto payment system**, backend development, or Laravel expertise:

*  LinkedIn: [https://www.linkedin.com/in/frank-daniel-773260282/](https://www.linkedin.com/in/frank-daniel-773260282/)
*  Open to freelance, contract, and remote roles



 If you find this useful, feel free to star the repository.
