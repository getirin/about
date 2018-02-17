# Getir.in
The main repo that explains our project, and shows our progress throughout the hackathon.

- **Team:**  Getir.in ([Yiğitcan 'Yengas' UÇUM](https://github.com/Yengas) and  [Çağatay './c²' ÇALI](https://github.com/cagataycali))
- **Project** [Getir.in](https://github.com/getirin)

[Backend](https://github.com/getirin/backend) - [Frontend](https://github.com/getirin/frontend)

## Project Definition
What is the purpose of the project, what problem does it try to solve?

### What does the project do?
Project aims to match people who wants products to be bought from nearby markets, and self registered couriers who buys and delivers these products. Can be thinken as the Uber-ified version of Getir. 

Note that this project doesn't deal with the applicability of the idea, security issues nor any set of thoughts on how to make this run in the real-world. It's just a presentation of our technical capabilities.

### Customers
Customer can pick products defined from a set of pre-defined list, and create orders. Carriers will send requests to fulfill these orders, in response the Customer will Accept or Reject.

In the event of a Carrier and Customer match, Customer will be able to track the Carrier location and his order progress.

### Carrier
Carrier can see the orders that aren't obtained by other couries in their surrounding. They can accept these offers by seeing the route they need to take to fulfill the order. 

### Markets
Each market has a pre-defined location and an endless supply of our products. Carrier will be shown the Market they need to go, and the person's address.

### Extra Features
There are some features we left out to keep the application possible in the time-frame we have been given.

#### Route optimization for Carrier
Carrier could process multiple orders at a time, with route optimization. At the Carrier UI this can be shown as a single route, or different routes on multiple pages. We have opted out to do this because of algorithmic complexity and additional UI requirements.

#### Additional progress update for orders
Carrier and Customers could talk with each other with a chat window, the Carrier could send set of updates, or we could have VOIP.

#### Market related features
The markets could have stocks, could have additional properties of what they offer(alcohol etc.), 
