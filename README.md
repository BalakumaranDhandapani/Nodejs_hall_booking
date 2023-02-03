# Nodejs_hall_booking_API_Backend
We have created an API for room Booking service for frontend to create a room, create a booking, view all rooms with booking details and view all bookings.

<b>Task:</b>

1.Creating a Room with features and price: PUT Method:
    https://hall-booking-dlb7.onrender.com/createRoom
    
    Ex: 
    {
    "noSeats": 3,
    "amenities": ["AC", "Geyser","Wifi","TV"],
    "price": 900
    }
    
2.Booking a Room with Customer Details: PUT Method:
    https://hall-booking-dlb7.onrender.com/createBooking
    
    Ex:
    {
    "custName": "Ananth",
    "date": "04/19/2022",
    "startTime": "11:00",
    "endTime": "22:00"
    }
    
3. Listing all Rooms with Booked details: GET Method:
    https://hall-booking-dlb7.onrender.com/getAllRooms
    
4. List all Customers with Booked data: GET Method:
    https://hall-booking-dlb7.onrender.com/getAllBookings
