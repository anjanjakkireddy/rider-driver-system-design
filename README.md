# rider-driver-system-design

## Rider Functions
1. Profile
2. requesting ride
3. making a payment
4. History of rides

## Driver functions
1. Profile
2. accepting a ride
3. receiving payment 
4. history of rides.



##Services :

### RegistrationService
a. FirstName, LastName
b. UserType (Rider, Driver)
c. CreditCard/BankAccount to be onFile
### RideRequestService
a. Source 
b. Destination
c. Time (Optional)
### DriverRideService
a. Source
b. Destination
c. Time (Optional)
### RideAcceptService
a. Rider details 
b. RideId
c. Store in Duplicate Check table
d. Store in RideAccept Table
### PaymentService
a. Make Payment (using Token)
### PaymentProfile 
a. Account 
