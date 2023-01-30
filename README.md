# Posta420
A short descirption 
The system will do the processess of a postal office.
The sender or the Branch will create a New order for a package to be delivered. The package will be sent to the warehouse and will be maintained by StorageWorker. There it will be sorted
filtered by address and will be sent either for "Delivering"(When the package is same city) or "Transit"(When package is on another city) by the StorageWorker. Then if the package is delivered
succesfully DeliveryMan changes the state from Delivering to "Delivered". If there happens a problem with the delivery the package will be sent to "Problematic" state by the DeliveryMan.
If the Package fails to deliver it will be sent to the reciever and to the Returned state.
