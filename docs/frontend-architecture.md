# Frontend Architecture & State Management

Structure and patterns adopted across the React client application.

## Structure
- `src/components`: Reusable UI elements and domain-specific view modules.
- `src/context`: React context providers for Authentication and Sidebar navigation.
- `src/utils`: Formatting, currency calculations, and third-party script loaders.

### State Management Rules
Global session state is centralized via Context API, while localized table/cycle data uses scoped custom hooks.
