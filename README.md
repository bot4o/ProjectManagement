# Project Management System

## Project Overview

A C++ desktop application developed during my software development internship at CSoft. The project focuses on workplace project management and demonstrates professional C++ development using Microsoft Foundation Classes (MFC).

The solution follows a multi-layered, component-based architecture, separating business logic, database operations, domain models and user interface components.

## Architecture

The application uses an MFC Multiple Document Interface (MDI) architecture with a Document/View-based presentation model.

### Components

- **ClientApp** – Main application executable. Manages the application lifecycle and coordinates communication between components.
- **Core.dll** – Shared utility library providing reusable functionality across application modules.
- **Domain.dll** – Contains data structures, business models and entities used throughout the application.
- **Database.dll** – Data access layer responsible for database operations, persistence and data retrieval.
- **Application.dll** – Business logic layer implementing application workflows and business rules.
- **Document.dll** – Presentation coordination layer connecting application logic, document management and UI components.
- **UIView.dll** – User interface layer implementing MFC view classes, including `CListView` and `CTreeView`.
- **UIDialog.dll** – Dialog-based interface components built using MFC `CDialog` classes.

## Technology Stack

- **Language:** C++
- **Framework:** Microsoft Foundation Classes (MFC)
- **Architecture:** Multi-layered, component-based architecture
- **UI Architecture:** MFC MDI, Document/View
- **Database:** Microsoft SQL Server
- **Platform:** Windows
- **Development Environment:** Visual Studio

## Architecture Principles

- **Separation of Concerns** – Each component has a dedicated responsibility.
- **Modularity** – Independent components organize application functionality.
- **Reusability** – Shared utilities and domain models are provided through common libraries.
- **Layered Design** – Database operations, business logic, presentation and UI are separated into distinct components.

## Component Dependencies

- All components use `Core.dll` for shared utilities.
- All components use `Domain.dll` for common data models and entities.
- UI components (`UIView.dll` and `UIDialog.dll`) interact through `Document.dll`.
- `Application.dll` handles business logic independently of the presentation layer.
- `Database.dll` manages database operations and data persistence.

## Learning Outcomes

- Professional C++ application development.
- MFC desktop application development.
- MDI and Document/View architecture.
- Multi-project Visual Studio solution management.
- Component-based software design.
- Database integration using C++.

## Project Context

Developed as part of my Software Developer Internship at **CSoft**, Varna, Bulgaria.

The repository contains the internship project source code, solution structure and architectural documentation.
