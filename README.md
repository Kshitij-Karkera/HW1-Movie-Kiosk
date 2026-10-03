# HW1-Movie-Kiosk
Guided software engineering tools practice

# Movie Theater Ticket Kiosk

This repository contains practice artifacts for a self-service movie theater ticket kiosk.
Customers use the kiosk to browse movies and showtimes, choose a seat, and purchase a ticket.
The system confirms each purchase and ensures that no seat is sold twice.

## Repository Contents

- `README.md` – Project overview
- `requirements.md` – Kiosk requirements
- `diagrams/` – UML diagrams (domain model, use case, sequence)

## Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The customer has selected a movie, a showtime, and an available seat.

**Main Steps:**
1. The customer chooses to purchase the selected seat.
2. The system places a temporary hold on the seat.
3. The system displays the ticket price.
4. The customer enters payment information.
5. The system processes the payment.
6. The system marks the seat as sold and creates a ticket.
7. The system displays a confirmation with the ticket details.

**Postcondition:** The ticket is issued, the payment is recorded, and the seat can no longer be sold for that showtime.
