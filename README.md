# Smart India Hackathon Workshop
## Date: 16-12-2025
## Register Number: 212223220080
## Name: Preethi J
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

Improper disposal of electronic waste (E-waste) is a growing environmental and health concern. Many people are unaware of nearby authorized e-waste collection centers, safe disposal methods, and the harmful impact of incorrect disposal. Due to lack of awareness and accessibility, a large amount of e-waste ends up in landfills, causing pollution and resource wastage.

This project aims to create a smart digital platform that helps users locate nearby e-waste recycling and collection facilities, learn about safe e-waste disposal, and encourage responsible recycling through incentives.


## Proposed Solution:

The proposed system is a web-based application that enables users to find the nearest authorized e-waste collection centers using location services and interactive maps.
### Key Features of the Solution:

* Location-Based Facility Finder
  - Uses Google Maps API to detect the user’s location.
  - Displays nearby e-waste collection and recycling centers with directions.

* E-Waste Awareness & Education
  - Provides information about different types of e-waste.
  - Explains environmental and health impacts of improper disposal.
  - Suggests correct disposal methods.

* Image Recognition (Optional / Advanced Feature)
  - Users can upload an image of an electronic item.
  - The system identifies the e-waste category and recommends suitable disposal facilities.

* Reward & Incentive System
  - Users earn reward points for proper e-waste disposal.
  - Encourages community participation and eco-friendly behavior.

* Admin & Analytics Module
  - Admin can manage facility data (add/update/delete centers).
  - Dashboard shows statistics such as number of users, facilities accessed, and recycling impact.

## Architecture Diagram

<img width="1024" height="745" alt="ChatGPT Image Dec 16, 2025, 11_54_06 AM(SA)" src="https://github.com/user-attachments/assets/6a83d1eb-b683-4aea-bde4-6445788a928c" />


## Use Cases
![WhatsApp Image 2025-12-16 at 12 13 41 PM](https://github.com/user-attachments/assets/faae31d6-d457-4edc-aa23-1eaa50cc462e)


## Technology Stack

* Frontend
  - React.js – UI framework for web interface.
* Backend
  - Node.js + Express – API server (router, business logic).
* Database
  - PostgreSQL
  - (Optionally with PostGIS for geospatial queries) — for points, distances.
* Third-Party Services
  - Google Maps API – Geolocation, mapping.
  - Auth Service / Firebox Authenticator – Login & authentication.
* Dev & Utility
  - Git – version control.
  - Postman / Insomnia – API testing tools.


## Dependencies

* Frontend (React)
  - react
  - react-dom
  - react-router
  - axios (for HTTP)
  - @google/maps or similar

* Backend (Node.js)
  - express
  - body-parser
  - cors
  - dotenv
  - pg (PostgreSQL client)
  - jsonwebtoken (if using JWT auth)
  - bcryptjs (password hashing)

* Database
  - PostgreSQL (with PostGIS if geospatial)
  - Tools: pgAdmin or DBeaver

* Tools/Testing
  - Postman/Insomnia
  - ESLint/Prettier

