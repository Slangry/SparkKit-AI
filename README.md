# SparkKit AI — early-stage MVP

SparkKit is a mobile-first toolkit concept for business ideas, product descriptions, email drafts, CV wording, study plans and text-first social posts.

## Current status

- Static responsive website; no build step required.
- Tools run in the browser and generate structured drafts from user input.
- Copy and clear controls work on mobile and desktop.
- No sign-up required; no user data is sent to a server by the current generator.
- **Important:** the current version uses structured templates, not a connected large language model. It is not yet a fully AI-operated product.
- No payments, subscriptions, analytics, ad network, user accounts or AI API have been connected.
- The example contact email uses a reserved placeholder domain and must be replaced before public promotion.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch `main` and folder `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site. The expected address is `https://slangry.github.io/SparkKit-AI/`.

## To make it truly AI-powered

Do not put a private model API key in browser JavaScript. Add a server-side API route or serverless function that reads the provider key from a secret/environment variable, validates inputs, applies rate limits and returns generated content. Then connect the UI to that route. You will need to choose a model provider, configure a key, estimate per-request costs and add abuse protection.

## Before monetization

- Replace the example contact address and publish accurate Terms and Privacy notices.
- Add an AI backend and test it across devices and countries.
- Add a privacy-conscious analytics tool and measure whether users return.
- Apply for an ad network only after the site has useful original content and meets that network's policies.
- If adding subscriptions, use a payment provider that supports the countries you intend to serve.
- Never promise users earnings or guaranteed outcomes.

## Local preview

Open `index.html` in a modern browser. No dependencies are required.
