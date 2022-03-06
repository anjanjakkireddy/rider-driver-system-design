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
  1. FirstName, LastName
  2. UserType (Rider, Driver)
  3. CreditCard/BankAccount to be onFile
### 2. RideRequestService
  1. Source 
  2. Destination
  3. Time (Optional)
### 3. DriverRideService
  1. Source
  2. Destination
  3. Time (Optional)
### 4. RideAcceptService
  1. Rider details 
  2. RideId
  3. Store in Duplicate Check table
  4. Store in RideAccept Table
### 5. PaymentService
  1. Make Payment (using Token)
### 6. PaymentProfile 
  1. Account 
