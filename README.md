# Shopify Cookieless Auth Demo
This is not sponsored or endorsed by Shopify, or connected with Shopify in any way.

I'm providing this package as a reference for using with Shopify's Next Gen JWT-based Cookieless Auth.

# Instructions
If you'd like to see this in action, it's important to create a new Shopif-CLI project.  

```sh
~/ $ shopify create project APP_NAME
```  
Choose Node.js App  
Then, clone this repo. Once you've cloned the demo, you can connect your newly created existing Shopify project to the demo. Open a terminal in the demo directory and use the command:
```shopify connect```
This will allow you to associate API keys and secrets, plus your ngrok tunnel with the project. Otherwise, you'll be missing the .env and .shopify-cli.yml files.

# Shopify App Node

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.md)
[![Build Status](https://travis-ci.com/Shopify/shopify-app-node.svg?branch=master)](https://travis-ci.com/Shopify/shopify-app-node)

Boilerplate to create an embedded Shopify app made with Node, [Next.js](https://nextjs.org/), [Shopify-koa-auth](https://github.com/Shopify/quilt/tree/master/packages/koa-shopify-auth), [Polaris](https://github.com/Shopify/polaris-react), and [App Bridge React](https://shopify.dev/tools/app-bridge/react-components).

## Installation

Using the [Shopify-App-CLI](https://github.com/Shopify/shopify-app-cli) run:

```sh
~/ $ shopify create project APP_NAME
```

Or, fork and clone repo

## Requirements

- If you don’t have one, [create a Shopify partner account](https://partners.shopify.com/signup).
- If you don’t have one, [create a Development store](https://help.shopify.com/en/partners/dashboard/development-stores#create-a-development-store) where you can install and test your app.
- In the Partner dashboard, [create a new app](https://help.shopify.com/en/api/tools/partner-dashboard/your-apps#create-a-new-app). You’ll need this app’s API credentials during the setup process.

## Usage

This repository is used by [Shopify-App-CLI](https://github.com/Shopify/shopify-app-cli) as a scaffold for Node apps. You can clone or fork it yourself, but it’s faster and easier to use Shopify App CLI, which handles additional routine development tasks for you.

## License

This respository is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
