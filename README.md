# Yu_Timothy_Bradburn_Kenneth_P0
Project0 Repository for Timothy Yu and Kenneth Bradburn
Update as of 10/11/2012

Robot adds a vendor as long as the information given to the robot in an Excel sheet matches a specific format. Our rationale being if this is for a store or webpage that information could be translated from HTML easily.

Robot can run an order that accounts for discounts and does not pull the order of an item if there is not enough in stock. Our reasoning is to not fulfill an order for a singular item in that order if we can not fully deliver. IE: A person wants 2 tires and 1 water. If our inventory shows 1 tire and 1 water. The Client will receive the water and we will have a printout showing that we could not fill the order of the tires. That way we could "delay" a shipment of the tires to them until we get an updated inventory. So they will be charged for the water and that will be processed but they will get a notice that tires will need to be restocked.

Robot in its current state can add a client, but the process needs further automation.

We need to add exception handling in some cases where we are trusting user input.

There is a method for updating the inventory now with a new shipment. The format has to account for items that we are not getting in and they have to be represented with a 0 number of incoming products.


-- MVP
- [x] Robot should be able to take client shopping lists and place orders on the appropriate vendors.
- [x] Robot should record the total expense of each shopping trip for each client.
- [ ] Robot should be able to record any items that were out of stock or not found.
- [x] Robot should be able to add clients to the existing client list and take in their shopping order.
- [x] Robot should be able to add more vendors in the existing vendor collection.
- [x] Robot should be able to take in account discounts noted by the vendors.

-- Stretch Goals
- [ ] Sending emails to clients about their shopping order
- [x] Notify clients about vendor discounts/sales
- [ ] Email vendors about out of stock items
- [x] Restock inventory for vendors
- [ ] Any other extra features that would improve UX

