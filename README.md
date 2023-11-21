## Next.js Sanity and Stripe E-Commerce

Other dependencies: shadcn, lucide-react, use-shopping-cart

## Getting Started

Install dependencies

```bash
npm i
```

First, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Sanity

- https://www.sanity.io/docs/create-a-sanity-project
- Project has been created but requires a Project ID to be added to a local .env to run correctly
- This requires the creation of a new sanity project via sanity.io
- Once the project is created the Project ID can be found in the sanity.io user dashboard
- Look at `sample.env` for the variable names to use

## Stripe

- Create a Stripe account
- The account does not need to be fully filled out to access developer features it just needs a verified email
- Once created go to the Stripe Dashboard [https://dashboard.stripe.com/test/dashboard](https://dashboard.stripe.com/test/dashboard)
- Get API Key of Publishable Key from Dashboard
- A product catalog will need to be created on Stripe for the products listed in this project
- The products listed can be found in PRODUCTS.md
- Once all products have been added into Stripe the Pricing API ID per product from Stripe should be added into Sanity for corelation between the services.
- In Stripe dashboard [https://dashboard.stripe.com/settings/checkout](https://dashboard.stripe.com/settings/checkout) client only integration needs to be enabled

## ENV Vars

- Stripe
- Sanity

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
