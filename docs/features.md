# Technical Specifications & Data Privacy — Wittlet by JE Horizon

## Architectural Principles

1. **Local-First Execution:** All business logic, calculation engines, and file operations execute directly on the local machine.
2. **Zero Telemetry:** The application does not include third-party tracking pixels, behavioural analytics, or background telemetry beacons.
3. **Storage Isolation:** Application data is stored in the user's isolated local app directory using secure local storage (SQLite with atomic write transactions, Windows DPAPI encryption).
4. **Resilient Offline Operation:** Full functionality remains accessible without an active internet connection.

## Key Feature Matrix

### Lightweight, floating desktop companion interface for Windows 10/11.

Operates entirely within local process memory and writes directly to local storage.
### Local conversational intelligence, casual games, and learning exercises.

Operates entirely within local process memory and writes directly to local storage.
### Operator-governed file tasks: review every proposed change before writing.

Operates entirely within local process memory and writes directly to local storage.
### Zero cloud recording: your conversations and desktop context stay private.

Operates entirely within local process memory and writes directly to local storage.
### Free to download and play with no recurring subscription fees.

Operates entirely within local process memory and writes directly to local storage.


## Security & Integrity

- **Database Engine:** Embedded SQLite with Write-Ahead Logging (WAL) and foreign-key constraints.
- **Data Boundaries:** Zero customer data is uploaded to remote servers during regular usage.
