# Manager Library — Public Presentation Page

This repository contains the static landing page for *Manager Library*, acting as the public-facing promotional and overview website for the platform.

##  Core SDD Architectural Decisions

Adhering strictly to the architectural constraints outlined in the specifications, this repository fulfills a specific, isolated role within the project ecosystem:

### 1. Static Isolation & Separation of Concerns
- **Zero API Dependencies:** This component is completely decoupled from the system's active backend database layers. It operates strictly as a read-only presentation website.
- **Privacy & Security Boundaries:** By design, this landing page does not handle, store, or expose any sensitive user credentials or personal member identification records (e.g., `document_number`, `password_hash`).
- **Clean Structure:** Built entirely using semantic HTML to outline core system benefits, operational boundaries, and internal role structures without adding unnecessary execution overhead.


