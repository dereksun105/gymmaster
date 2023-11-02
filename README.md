# Gym Management and Booking System (GymBoS)

## Overview
GymBoS is a streamlined web application designed to manage gym memberships, class bookings, and room scheduling. This system simplifies the process of managing gym operations and provides an easy interface for members to book classes.

## Features
- **Member Management**: Add, update, and remove members from the system.
- **Class Scheduling**: Create and manage class schedules including time, duration, and location.
- **Booking System**: Members can book classes, and the system tracks attendance and booking status.
- **Room Management**: Manage different rooms where classes take place, including capacity management.

## Technology Stack
- **Frontend**: Streamlit
- **Backend**: Python
- **Database**: MySQL

## Database Design
The database consists of the following tables:
- `Members`: Contains member information.
- `Classes`: Holds information about the classes offered.
- `Bookings`: Tracks which members are booked for which classes.
- `ClassTypes`: Provides descriptions of different class types.
- `Rooms`: Contains information about the rooms where classes are held.

## Getting Started
To get started with GymBoS, follow these steps:

### Prerequisites
- Python 3.8 or higher
- MySQL Server
- Streamlit

### Installation
1. Clone the repository:
```bash
git clone [URL to your repository]
