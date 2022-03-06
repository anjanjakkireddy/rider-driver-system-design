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



## Services :

### 1. RegistrationService
a. FirstName, LastName
b. UserType (Rider, Driver)
c. CreditCard/BankAccount to be onFile
### 2. RideRequestService
a. Source 
b. Destination
c. Time (Optional)
### 3. DriverRideService
a. Source
b. Destination
c. Time (Optional)
### 4. RideAcceptService
a. Rider details 
b. RideId
c. Store in Duplicate Check table
d. Store in RideAccept Table
### 5. PaymentService
a. Make Payment (using Token)
### 6. PaymentProfile 
a. Account 
