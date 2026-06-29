Vehicle Service System using Abstraction
Develop a Vehicle Service System in Java using the concept of Abstraction.

Requirements:
Create an abstract class VehicleService with the following data members:
customerName
vehicleNumber
serviceType

Include:
A constructor to initialize the data members.
An abstract method calculateServiceCharge() to calculate the service cost.
A concrete method displayServiceDetails() to display the customer and vehicle details.
Create the following subclasses:
CarService
BikeService

Each subclass should:
Include an additional data member sparePartsCost.
Override the calculateServiceCharge() method.

Calculate the service charge as follows:
Car Service: ₹2000 + Spare Parts Cost
Bike Service: ₹800 + Spare Parts Cost
Display the customer details, vehicle details, spare parts cost, and total service charge.

In the main() method:
Create objects for both CarService and BikeService.
Use an abstract class reference to invoke the overridden methods and demonstrate Runtime Polymorphism.
