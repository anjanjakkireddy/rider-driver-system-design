# rider-driver-system-design

## Rider Functions
-- Profile
-- requesting ride
-- making a payment
-- History of rides

## Driver functions
-- Profile
-- accepting a ride
-- receiving payment 
-- history of rides.



##Services :

### RegistrationService
	-- FirstName, LastName
	-- UserType (Rider, Driver)
	-- CreditCard/BankAccount to be onFile
### RideRequestService
	-- Source 
	-- Destination
	-- Time (Optional)
### DriverRideService
	-- Source
	-- Destination
	-- Time (Optional)
### RideAcceptService
	-- Rider details 
	-- RideId
	-- Store in Duplicate Check table
	-- Store in RideAccept Table
### PaymentService
	-- Make Payment (using Token)
### PaymentProfile 
	-- Account 
