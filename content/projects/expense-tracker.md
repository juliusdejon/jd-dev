---
title: Expense Tracker 🤖
date: 2023-11-10
description: Scan Receipts texts through Google Document AI.
math: true
categories: ["node", "gcp", "ai"]
featured: true
cover: /projects/expense-tracker/ai-logo.svg
---

### Demo

Code: [https://github.com/juliusdejon/expense-tracker-google-document-ai](https://github.com/juliusdejon/expense-tracker-google-document-ai)

### Inspiration

I am currently exploring solutions to efficiently track my grocery expenses by automating the process of uploading a receipt and saving the extracted data automatically, eliminating the need for manual entry.

I attempted to find a cost-free method to upload my receipts and leverage AI capabilities for automated processing. Unfortunately, all the available applications offering this service come with a fee for uploading receipts.

Therefore, I decided to create a Proof of Concept utilizing Google Cloud Document AI to upload and process my receipts, making use of the remaining $300 in credits to track my expenses.

### POC features

We can use the API google cloud via Node.js to process custom processor

### Usage

Create a Document AI processor (specifically expense processor)
Supply needed environment variables (see .env.example)
Replace the receipt.pdf with your image file (it must be pdf too)
Run node index.js

### Screenshots

![receipt](/projects/expense-tracker/receiptExample.png "receipt")

![result](/projects/expense-tracker/result.png "result")
