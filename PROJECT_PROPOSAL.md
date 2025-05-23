# Project Proposal - Sauna Booking System

## General Description
An interactive web application for hotel sauna booking management with dual interfaces for guests and front office staff. The system streamlines reservations, enforces booking policies, and provides real-time availability tracking.

## Available Functionalities

### Guest Interface
- QR code scanning for booking access
- Booking form with validation:
  - Guest name(s)
  - Date/time selection (6am-1am)
  - Room number
  - Guest count (max 4)
- Booking confirmation display
- Real-time availability checking

### Front Office Interface
- Staff authentication (JWT)
- Dashboard showing current sauna usage
- Booking management:
  - Create/cancel reservations
  - Mark sessions complete
  - View daily/upcoming bookings
- Override capabilities:
  - Exception bookings (up to 6 people)
  - Extended hours booking
- Real-time synchronization

## Technical Implementation
- Frontend: Vue 3, Pinia, Vue Router
- Backend: PHP REST API
- Authentication: JWT tokens
- Database: MySQL
- Features: QR code generation, real-time updates
