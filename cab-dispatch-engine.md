## Cab Dispatch Engine

### Goal

Consider an Online Cab Booking Service called "Fuber" which has a fleets of cab in a city. Fuber provides a Mobile App which allows its customers to request for a cab to go from point A to Point B. You need to design a micro service that expose an API that takes the current location of the customer and assigns a nearest cab to him. As soon as cab is assigned to a customer, it shouldn't be available to other customers. Customers can specify some specific attributes of the cab - like size / color as well as maximum distance that the cab can be from the customer's current location.

### Deliverables

- Design a RESTFul API that performs the booking
- Design a CLI App that can drive the entire workflow -> Create Cabs, Create customers, Create Bookings etc
- Design a suite of full integration test that ensures that dispatch engine works properly - aka always return the closest taxi, prevents double booking, handles user preferences etc - try doing this without mocking

### Extra Credits
- Design a mechanism to provide a live status update of the cab location to the customer.

### Notes
- We can assume that distance between pair of Lat/Longs can be calculated by regular Coordindate Geometry
- You can build this in any programming language
- There is no fixed time limit for the assignment. Ideally you shouldn't spend more than 4-5 hours on this
- One of the core areas we want to test out is ability to deal with concurrency. Hence, we would like
you to design your solution without any external store. Ensure that you use proper set of abstractions that allow you to change to a proper DB if you ever need to do so
- While we are not looking for a distributed solution here, in practice such microservices exists in a distributed world. So think through how would you handle all the challenges that arise  if this were run in production in a distributed environment
- Call us if you have any trouble understading anything
- Most importantly, have fun building it :) :)
