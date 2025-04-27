---
sidebar_position: 1
---

# Introduction

Internal Docs for prices tracker application.

## Purpose

- The purpose of this prices tracker application is to track prices of groceries, clothing, pet supplies, mechanic services, etc.
  - This benefits consumers to quickly research items, primarily the prices per quantity, among multiple stores.

## App Features

- **Add Forms**:
  - Add a new store
  - Add a new item
- **Modify button**: Modify information about an item or store
- **Delete button**: Delete an item or store.
  - Admins Access only?
- **View Dashboard**: Pick a store and see list of items
- **Search**: The user can search for specific items within our database or from third-party apis with public item information.
  - Enable Location and integrate Apple/Google Maps to find direction to store fast.
- **Barcode Scanner**: The user can use their smart phone's camera to scan the barcode of items to:
  - Add a new item to the system
  - Find item info based on barcode
  - Modify an item based on barcode. Perhaps, setting an alert that there is a sale ongoing.
- **Login**: Allow guest login via email or phone number with quick authentication code to login without a password.
- **AI Chat Bot**: The user can start a conversation with the text-based AI chat bot to quickly compare prices between multiple items among multiple stores with a given breakdown of all relevant info.
- **Donate Button**: Integrate a payment button like Paypal to receive donations.

## Tech Stack

- React Typescript for frontend
  - NGINX is a reverse proxy to serve the built static files of your React application.
    - This setup is used to improve performance and manage routing in production environments.
- Kotlin Spring Boot for backend
