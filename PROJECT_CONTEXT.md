# HomeHub Project Context

## Product Overview

HomeHub is a production-grade SaaS platform for homeownership management. It connects homeowners with trusted service providers and aims to become the central hub for everything related to home ownership.

## Product Vision

HomeHub is an AI-first homeownership platform that connects homeowners with trusted service providers while becoming the central hub for everything related to home ownership.

## MVP Focus

The MVP focuses on a marketplace where homeowners can request home services and receive quotes from verified providers.

## Target Users

### Homeowners
- Request home services
- Manage multiple homes
- Compare provider quotes
- Book services
- Review completed jobs
- Track service history

### Service Providers
- Register a company
- Complete business verification
- Upload licenses and insurance
- Select service categories
- Configure service areas by ZIP code
- Receive service requests
- Submit quotes
- Manage bookings
- Maintain company profiles
- View ratings and reviews

### Admins
- Verify providers
- Manage homeowners
- Manage providers
- Moderate reviews
- Manage service requests
- Access analytics dashboard

## Future Users

- Insurance companies
- Mortgage lenders
- Home warranty companies
- Utility providers
- Real estate agents
- Home inspectors

## Long-Term Vision

The long-term vision is to become the operating system for home ownership.

Instead of using multiple websites for contractors, insurance, mortgage, maintenance, utilities, warranties, documents, and AI assistance, homeowners will manage everything inside HomeHub.

The application should be designed to scale into a complete home management platform.

## Core MVP Features

### Homeowners
- Register/Login
- Manage multiple homes
- Create service requests
- Upload photos
- Receive multiple quotes
- Compare providers
- Book providers
- Review completed jobs
- Track service history

### Providers
- Register company
- Business verification
- Upload license and insurance
- Select service categories
- Configure service areas (ZIP codes)
- Receive service requests
- Submit quotes
- Manage bookings
- Manage company profile
- View ratings and reviews

### Admin
- Verify providers
- Manage homeowners
- Manage providers
- Moderate reviews
- Manage service requests
- Analytics dashboard

## Initial Service Categories

- Plumbing
- HVAC
- Electrical
- Roofing
- Lawn Care
- Pest Control
- Cleaning
- Painting

## Future Features

- Insurance management
- Mortgage management
- Utility management
- Home warranties
- Home maintenance reminders
- AI home assistant
- AI issue detection from uploaded images
- Home value tracking
- Document management
- Smart home integrations

## Core Domain Model

The central domain is "Home".

A homeowner can own multiple homes.

Each home contains:
- Address
- Documents
- Service history
- Maintenance records
- Insurance
- Mortgage
- Utilities
- Future AI recommendations

## Technology Stack

### Backend
- Java 21
- Spring Boot 3
- Gradle
- PostgreSQL
- Flyway
- Spring Security
- JWT Authentication
- Docker
- REST APIs
- OpenAPI

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- React Query
- React Hook Form

### Infrastructure
- Docker Compose
- GitHub Actions
- Nginx
- AWS (future deployment)

## Development Approach

This is an AI-first software project.

Every feature must have:
- Product requirements
- Business rules
- Database schema
- API specification
- UI wireframes
- Test cases
- AI implementation prompts

The application should follow:
- Domain Driven Design (DDD)
- Feature-based architecture
- Clean Architecture principles
- SOLID principles
- Production-quality coding standards
- High test coverage
- Scalable and maintainable design

## Goal

The goal is to build a long-term SaaS platform, not just a home services marketplace.
