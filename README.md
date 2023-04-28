# DatabaseDesign

Database design based off of the following prompt:

Bobcat Truck Rentals (BTR) needs to maintain data about manufacturers, trucks, employees, customers, and
rental transactions. BTR has trucks from several different truck manufacturers. A manufacturer maintained in
the database must have at least one truck in BTR’s fleet. For each manufacturer, the following information needs
to be maintained: manufacturer ID, manufacturer name, manufacturer street address, city, state, zip code, country,
contact person’s name, and contact phone. Information about each truck that needs to be maintained include the
truck ID, model, year, size (e.g., 12 feet, 16 feet, 22 feet), load capacity, floor space, odometer mileage, base daily
rental charge, and vehicle identification number (VIN). Each truck may be associated with many rental
transactions, or it may not have been rented yet (a new truck). A customer could have rented a truck more than
once from BTR; however, to be considered a customer, s/he should have rented a truck at least once. Customer
information to be maintained includes the customer ID, first name, last name, street address, city, state, zip code,
date of birth, driver license number and state, and phone number. Each truck rental transaction is associated with
a truck and a customer. For each rental transaction, information regarding the rental transaction number, rental
date, return date, mileage out, mileage in, actual daily rental charge, refuel charge, and total rental charge needs
to be maintained. Each employee can process zero or many rental transactions, and each rental transaction may
be processed by more than one employee. It is necessary to maintain comments inputted by each employee for
transactions processed. For each employee, it is necessary to maintain employee ID, first name, last name, middle
name, gender, home street address, city, state, zip code, phone number, birth date, and salary. The manufacturer
ID, truck ID, employee ID, customer ID, and rental transaction number uniquely identify each manufacturer,
truck, employee, customer, and rental transaction, respectively.
