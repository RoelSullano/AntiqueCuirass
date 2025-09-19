# Antique Cuirass E-Commerce Website

A specialized e-commerce platform for antique military equipment, particularly cuirasses and historical armor pieces.

## Project Overview

This project is built for selling authentic antique military equipment with a focus on:
- French Napoleonic Cuirasses
- Medieval Armor
- Military Antiques
- Historical Weapons

## Tech Stack

- **Backend**: PHP 8.0+
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Database**: FileMaker (converted to JSON for development)
- **Version Control**: GitHub
- **Team Size**: 4 members

## Database Structure

The project uses a FileMaker database with the following main entities:
- **Products**: Antique items with detailed specifications
- **Categories**: Hierarchical category system (Military Antiques > Medieval Armor > Cuirasses)
- **Customers**: User management and authentication
- **Orders**: Order management and tracking
- **Product_Images**: Image gallery for products

## Team Structure & Responsibilities

### Team Member 1: Backend Developer & Database Integration
**Responsibilities:**
- FileMaker Data API integration
- PHP backend development
- API endpoint creation
- Database connection and queries
- Security implementation

### Team Member 2: Frontend Developer & UI/UX
**Responsibilities:**
- HTML/CSS/JavaScript development
- Responsive design implementation
- User interface design
- Product catalog and shopping cart
- Checkout process

### Team Member 3: Full-Stack Developer & Features
**Responsibilities:**
- User authentication system
- Order management system
- Admin panel development
- Search and filtering functionality
- Payment integration

### Team Member 4: Project Manager & Quality Assurance
**Responsibilities:**
- Project coordination
- Testing and quality assurance
- Documentation
- Deployment and DevOps
- Team communication

## Project Structure

```
antique-cuirass-ecommerce/
├── backend/
│   ├── api/
│   ├── config/
│   ├── models/
│   ├── controllers/
│   └── database/
├── frontend/
│   ├── assets/
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── pages/
│   └── components/
├── admin/
│   ├── dashboard/
│   ├── products/
│   ├── orders/
│   └── customers/
├── docs/
├── tests/
└── config/
```

## Getting Started

1. Clone the repository
2. Set up local development environment
3. Configure FileMaker connection
4. Install dependencies
5. Run the application

## Development Workflow

- Use feature branches for development
- Code reviews before merging to main
- Regular team meetings and updates
- GitHub Issues for task tracking

## Security Considerations

- FileMaker server not exposed to internet
- Secure API endpoints
- Input validation and sanitization
- HTTPS implementation
- User authentication and authorization
