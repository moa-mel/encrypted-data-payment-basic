# Unlock Encrypted Data with a Fiber Payment

A practical demonstration of payment-gated access to encrypted data using [Fiber](https://www.fiber.world/).

This project explores how a provider can make encrypted data available to a buyer and grant access after the required payment has been completed.

## Project Screenshots

The following screenshots document the application and its workflow.

### Screenshot 1

![Application screenshot 1](images/Screenshot%202026-11-23%20at%2010.03.33.png)

### Screenshot 2

![Application screenshot 2](images/Screenshot%202026-11-23%20at%2010.03.41.png)

### Screenshot 3

![Application screenshot 3](images/Screenshot%202026-11-23%20at%2010.03.49.png)

### Screenshot 4

![Application screenshot 4](images/Screenshot%202026-11-23%20at%2010.04.26.png)

### Screenshot 5

![Application screenshot 5](images/Screenshot%202026-11-23%20at%2010.04.52.png)

### Screenshot 6

![Application screenshot 6](images/Screenshot%202026-11-23%20at%2010.05.07.png)

### Screenshot 7

![Application screenshot 7](images/Screenshot%202026-11-23%20at%2010.05.33.png)

### Screenshot 8

![Application screenshot 8](images/Screenshot%202026-11-23%20at%2010.05.52.png)

### Screenshot 9

![Application screenshot 9](images/Screenshot%202026-11-23%20at%2010.06.25.png)

## What This Project Demonstrates

The project demonstrates how Fiber payment channels can be used in an application where payment determines access to protected digital resources.

The general workflow is:

1. **Resource preparation:** The provider prepares and publishes the protected resource.
2. **Buyer access request:** The buyer opens the application and requests access.
3. **Payment initiation:** The buyer initiates payment through Fiber.
4. **Payment verification:** The application checks that the payment has completed successfully.
5. **Resource unlocking:** Once payment is confirmed, the buyer can access the protected data.

The central concept is connecting payment completion to access authorization.

## Why Fiber?

Fiber provides payment-channel infrastructure that can support applications requiring efficient payment interactions.

In this project, Fiber is used as part of an access-control workflow. Payment becomes the condition that determines whether a buyer can access a digital resource.

This pattern could be useful for:

- Paid research reports and documents.
- Premium API responses.
- Private datasets.
- Pay-per-use digital services.
- Subscription and membership content.

## Tutorial Reflection

One thing I appreciated about the tutorial was having explanations alongside the interactive steps. It made the process easier to follow because I could understand the purpose of an action while carrying it out, rather than constantly switching between the implementation and separate documentation.

I also liked that the tutorial connected the payment mechanism to a practical use case. Paying to unlock a resource made the relationship between a Fiber payment channel and access to valuable digital content easier to understand.

The part that stood out to me most was how the pattern can extend beyond a single protected resource. It could also be used for paid API access, private datasets, and other digital resources where access should depend on a successful payment.

Overall, the tutorial helped me think about Fiber payment channels as part of a complete application flow—not just as a way to move funds, but as a building block for applications that provide access to digital resources.

## Resources

- [Fiber encrypted data payment tutorial](https://www.fiber.world/docs/build/encrypted-data-payment)
- [Fiber documentation](https://www.fiber.world/docs)
- [Project repository](https://github.com/moa-mel/encrypted-data-payment-basic)