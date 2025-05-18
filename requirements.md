# Backend Requirements Specification

## Feature 1: User Authentication

### API Endpoints

- `POST /api/auth/register` — Register a new user
- `POST /api/auth/login` — Authenticate user and return JWT token
- `POST /api/auth/logout` — Log out user

### Validation Rules

- Name is required
- Email must be valid and unique
- Password must be at least 8 characters, alphanumeric

---

## Feature 2: Property Management

### API Endpoints

- `POST /api/properties` — Create a new property listing
- `GET /api/properties` — Retrieve all property listings
- `GET /api/properties/:id` — Retrieve a single property
- `PUT /api/properties/:id` — Update an existing property
- `DELETE /api/properties/:id` — Delete a property

### Validation Rules

- Title, location, and description are required
- Price must be a positive number
- At least one image is required

---

## Feature 3: Booking System

### API Endpoints

- `POST /api/bookings` — Book a property
- `GET /api/bookings` — Retrieve all bookings for a user
- `GET /api/bookings/:id` — Retrieve a specific booking
- `DELETE /api/bookings/:id` — Cancel a booking

### Validation Rules

- Valid property ID required
- Check-in date must precede check-out date
- Booking dates must not conflict with existing bookings