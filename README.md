# TravelAgency
## Data to be stored
- Hotel
    - Name
    - Number of stars
    - Address
    - Link
    - Short description

- Trips
    - Destination
    - Travel mode (plane, car, ship, train) (FK -> separate table)
    - Departure
    - Arrival
    - Hotel (FK)
    - Travel cost
    - Short description
    - Number of people
    - Pictures (e.g. from the hotel, from the place, from the surroundings)

- Registrations
    - Name
    - Number of people
    - Email
    - Phone
    - Trip (FK)

## Functions
- Admin functions
    - Storing hotel data
    - Storing trip data
    - Querying registrations

- Customer functions (no login required)
    - Listing trips
        - Filtering by destination
        - Filtering by travel mode
        - Filtering by time
    - Registration for the trip

# Angular Part:

HTML és CSS létrehozása:
- Login ablak

Admin képernyők:
- Szállodák listázása, módosítása, törlése, új rögzítése
- Ajánlatok listázása, módosítása, törlése, új rögzítése
- Jelentkezések listázása

Publikus képernyők
- Utazások listázása ( Szűrés: úti célra, utazási módra, időpontra)
- Regisztráció az utazásra