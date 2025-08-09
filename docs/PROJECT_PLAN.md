# RestoMate - Japanese Restaurant Management System

## Project Overview
A full-stack restaurant management system built with React (frontend) and Laravel (backend), designed for Japanese restaurants (ramen, sushi, izakaya, etc.) with Agile development approach.

## Tech Stack
- **Backend**: Laravel 11, MySQL, phpMyAdmin
- **Frontend**: React 18, Vite, Tailwind CSS
- **Design**: StarUML for diagrams, Tailwind CSS for styling
- **Database**: MySQL with proper relationships

## Product Backlog (User Stories)

### Epic 1: Worker Management
- **US001**: As a manager, I want to add new workers so I can manage staff
- **US002**: As a manager, I want to view all workers so I can see who's working
- **US003**: As a manager, I want to edit worker details so I can update information
- **US004**: As a manager, I want to delete workers so I can remove former staff
- **US005**: As a manager, I want to assign roles to workers so I can organize staff

### Epic 2: Menu Management
- **US006**: As a chef, I want to add menu items so I can update the menu
- **US007**: As a chef, I want to link ingredients to menu items so I can track what's needed
- **US008**: As a manager, I want to set prices so I can manage costs

### Epic 3: Inventory & Ingredients
- **US009**: As a chef, I want to track raw ingredients so I know what's in stock
- **US010**: As a chef, I want to track processed ingredients so I can plan prep work
- **US011**: As a manager, I want to see stock levels so I can order supplies

### Epic 4: Orders & Tables
- **US012**: As a server, I want to create orders so I can serve customers
- **US013**: As a server, I want to assign tables so I can manage seating
- **US014**: As a cashier, I want to process payments so I can complete orders

### Epic 5: Reports & Analytics
- **US015**: As a manager, I want to see sales reports so I can track performance
- **US016**: As a manager, I want to see staff performance so I can manage productivity

## Sprint Planning

### Sprint 1: Worker Management (2-3 days)
**Goal**: Basic worker CRUD operations with simple UI

**User Stories**:
- US001: Add new workers
- US002: View all workers  
- US003: Edit worker details
- US004: Delete workers
- US005: Assign roles

**Deliverables**:
- Worker database table and model
- Laravel API endpoints for workers
- React components for worker management
- Basic UI with Tailwind CSS

**Database Design**:
- Workers table with basic fields
- Roles table for different positions

### Sprint 2: Menu & Basic Ingredients (3-4 days)
**Goal**: Menu management with ingredient tracking

**User Stories**:
- US006: Add menu items
- US007: Link ingredients to menu items
- US008: Set prices

### Sprint 3: Orders & Tables (4-5 days)
**Goal**: Basic order management system

**User Stories**:
- US012: Create orders
- US013: Assign tables
- US014: Process payments

### Sprint 4: Advanced Inventory (5-6 days)
**Goal**: Complex ingredient transformation system

**User Stories**:
- US009: Track raw ingredients
- US010: Track processed ingredients
- US011: Stock level management

### Sprint 5: Reports & Polish (3-4 days)
**Goal**: Analytics and system refinement

**User Stories**:
- US015: Sales reports
- US016: Staff performance

## Database Design Strategy
- Start with simple tables for Sprint 1
- Add relationships and complexity in later sprints
- Use proper foreign keys and constraints
- Plan for ingredient transformation system

## Git Workflow
- **Main branch**: Production-ready code
- **Feature branches**: One per sprint (e.g., `RestoMate-1`)
- **Commit regularly**: Small, meaningful commits
- **Merge strategy**: Feature branch → Main after sprint completion

## Development Approach
- **Agile**: 2-3 week sprints with working deliverables
- **Database First**: Design tables before coding
- **API First**: Build Laravel backend, then React frontend
- **Simple UI**: Start with basic Tailwind components, enhance later

## Next Steps for Sprint 1
1. ✅ Create project plan (DONE)
2. 🔄 Design Worker UML diagram in StarUML
3. 🔄 Create database migrations
4. 🔄 Build Laravel models and API
5. 🔄 Create React components
6. 🔄 Connect frontend and backend
7. 🔄 Test and deploy Sprint 1

## Notes
- Start simple, add complexity gradually
- Focus on working features over perfect design
- Use Japanese restaurant terminology where appropriate
- Keep UI clean and professional
