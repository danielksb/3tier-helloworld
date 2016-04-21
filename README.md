# 3tier-helloworld

Write an application which helps to organize and manage (purchase) orders.
A typical worflow starts with a customer placing an order, which consists of a single product. The customer chooses this product from a list of preconfigured products, which is maintained by the product manager. Once a product is ordered, a sales agent may see the order, edit it and marks it ready for delivery. The distributor delivers the product and closes the order.

## Personae dramatis

* Customer
  * places orders
* Product Manager
  * organises list of available products
* Sales Agent
  * validates orders, may also change an order
* Distributor
  * delivers ordered product

## Milestone 1

* As a customer, I want to order a product from a preconfigured list, so that the order ist avaiable to the sales agents.
  * the order must contain the selected product and the customer's name
* As a product manager, I want to configure a list of products so that customers can choose from them.
  * a product must have a name and a description
* As a sales agent, I want to see all orders so that I can find newly placed orders as well as already delivered ones.
* As a sales agent, I want to mark a new orders so that they will be available for distributors.
* As a distributor, I want to see all orders already validated by the sales agents, but no orders which are already delivered.
* As a distributor, I want to mark orders as delivered.

