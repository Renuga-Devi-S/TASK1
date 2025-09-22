# TASK1
# Domain 
Hotel Management Database 
The chosen domain for this project is Hotel Management. This database is designed to efficiently manage hotel operations, including guest information, room allocation, reservations, payments, staff, and additional services such as laundry, spa, and food delivery. It aims to streamline day-to-day hotel management tasks and improve service tracking.

# ER diagram 
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/3da8f8ea-b952-4b06-baa4-0dec1c8a475e" />

# Database Contains 

The database consists of the following tables:
1. Guests: Stores customer details.
2. Rooms: Stores hotel room information.
3. Reservations: Manages guest bookings.
4. Payments: Stores payment details for reservations.
5. Staff: Contains records of hotel employees, their roles, and salaries.
6. Services: Lists extra services offered by the hotel.
7. GuestServices: A mapping table linking guests with the services they used.

# Relationships

* A guest can have multiple reservations.
* A room can be booked in multiple reservations over time.
* Each reservation is associated with a single payment.
* A guest can use multiple services, tracked via the GuestServices mapping table.
