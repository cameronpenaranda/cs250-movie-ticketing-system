Movie Ticketing System — Database Design

Overview
The database stores customers, movies, theaters, auditoriums, showtimes, seats, concession items, orders, tickets, and payments.
Main tables
User, Movie, Theater, Auditorium, Showtime, Seat, ConcessionItem, Order, Ticket, Payment
Relationships
Each theater contains auditoriums; each auditorium contains seats. Each movie has showtimes. Customers create orders containing tickets and concessions.
Data integrity
Prevent duplicate seat sales, maintain valid relationships, preserve successful purchases, and protect sensitive information.
