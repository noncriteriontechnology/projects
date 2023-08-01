# projects
All project we developed while learning technologies 

Develop barber shop application with following entities.

Shop Entity:

Represents the barber shop.
Attributes: shopId, shopName, location, contactNumber, etc.
Relationships: A shop can have multiple seats for customers to book appointments.

Seat Entity:

Represents a seat or chair in the barber shop.
Attributes: seatId, seatNumber, description, availabilityStatus, etc.
Relationships: A seat belongs to one shop and can have multiple appointments.

Customer Entity:

Represents a customer who wants to book appointments.
Attributes: customerId, firstName, lastName, email, phoneNumber, etc.
Relationships: A customer can have multiple appointments.

Barber Entity:

Represents a barber working in the shop.
Attributes: barberId, firstName, lastName, specialization, phoneNumber, etc.
Relationships: A barber can have multiple appointments.

Appointment Entity:

Represents an appointment booked by a customer.
Attributes: appointmentId, appointmentDateTime, status (e.g., booked, canceled), etc.
Relationships: An appointment is associated with one customer, one barber, and one seat.

Service Entity:

Represents different services offered in the shop (e.g., haircut, shave, etc.).
Attributes: serviceId, serviceName, description, duration, price, etc.
Relationships: A service can be associated with multiple appointments.

Payment Entity:

Represents a payment made by a customer for an appointment.
Attributes: paymentId, paymentAmount, paymentDateTime, paymentStatus, etc.
Relationships: A payment is linked to one appointment.
