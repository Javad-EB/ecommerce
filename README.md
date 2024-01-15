# ApexMarket - Full Stack E-Commerce App

## Overview

ApexMarket is a modern and feature-rich E-Commerce application built with Next.js, Stripe, TypeScript, Tailwind CSS, and Payload CMS. This project includes a user-friendly frontend, a secure payment system powered by Stripe, and an intuitive admin dashboard using Payload CMS.

## Features

- **User-Friendly Interface:** ApexMarket provides a seamless and responsive user experience for both customers and administrators.

- **Secure Payments with Stripe:** Integrated Stripe for secure and convenient payment processing.

- **Admin Dashboard & CMS:** Utilizes Payload CMS for easy content management and an intuitive admin dashboard.

- **TypeScript:** The project is developed using TypeScript for improved code quality and maintainability.

- **Tailwind CSS:** Employs Tailwind CSS for a highly customizable and utility-first styling approach.

- **Next.js:** Utilizes Next.js for server-side rendering, optimized performance, and a great developer experience.

# Payload E-Commerce Template

This is the official [Payload E-Commerce Template](https://github.com/payloadcms/payload/blob/main/templates/ecommerce). Use it to power e-commerce businesses and online stores of all sizes. This repo includes a fully-working backend, enterprise-grade admin panel, and a beautifully designed, production-ready website.

This template is right for you if you are selling:

- Physical products like clothing or merchandise
- Digital assets like ebooks or videos
- Access to content like courses or premium articles

Core features:

- [Pre-configured Payload Config](#how-it-works)
- [Authentication](#users-authentication)
- [Access Control](#access-control)
- [Shopping Cart](#shopping-cart)
- [Checkout](#checkout)
- [Paywall](#paywall)
- [Layout Builder](#layout-builder)
- [SEO](#seo)
- [Website](#website)

## Quick Start

To spin up this example locally, follow these steps:

### Clone

If you have not done so already, you need to have standalone copy of this repo on your machine. If you've already cloned this repo, skip to [Development](#development).

#### Method 1 (recommended)

  Go to Payload Cloud and [clone this template](https://payloadcms.com/new/clone/ecommerce). This will create a new repository on your GitHub account with this template's code which you can then clone to your own machine.

#### Method 2

  Use the `create-payload-app` CLI to clone this template directly to your machine:

    npx create-payload-app@latest my-project -t ecommerce

#### Method 3

  Use the `git` CLI to clone this template directly to your machine:

    git clone -n --depth=1 --filter=tree:0 https://github.com/payloadcms/payload my-project && cd my-project && git sparse-checkout set --no-cone templates/ecommerce && git checkout && rm -rf .git && git init && git add . && git mv -f templates/ecommerce/{.,}* . && git add . && git commit -m "Initial commit"

### Development

1. First [clone the repo](#clone) if you have not done so already
1. `cd my-project && cp .env.example .env` to copy the example environment variables
1. `yarn && yarn dev` to install dependencies and start the dev server
1. `open http://localhost:3000` to open the app in your browser

That's it! Changes made in `./src` will be reflected in your app. Follow the on-screen instructions to login and create your first admin user. To begin accepting payment, follow the [Stripe](#stripe) guide. Then check out [Production](#production) once you're ready to build and serve your app, and [Deployment](#deployment) when you're ready to go live.

## Website

This template includes a beautifully designed, production-ready front-end built with the [Next.js App Router](https://nextjs.org), served right alongside your Payload app in a single Express server. This makes is so that you can deploy both apps simultaneously and host them together. If you prefer a different front-end framework, this pattern works for any framework that supports a custom server. If you prefer to host your website separately from Payload, you can easily [Eject](#eject) the front-end out from this template to swap in your own, or to use it as a standalone CMS. For more details, see the official [Custom Server Example](https://github.com/payloadcms/payload/tree/main/examples/custom-server).

Core features:

- [Next.js App Router](https://nextjs.org)
- [Stripe](https://stripe.com)
- [GraphQL](https://graphql.org)
- [TypeScript](https://www.typescriptlang.org)
- [React Hook Form](https://react-hook-form.com)
- [Payload Admin Bar](https://github.com/payloadcms/payload-admin-bar)
- Authentication
- Publication workflow
- Shopping cart
- Checkout
- Customer accounts
- Dark mode
- Pre-made layout building blocks
- SEO
- Redirects
- Paywall
