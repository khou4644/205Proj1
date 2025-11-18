
Here’s a **brief per-member instruction** for using the **feature branch workflow** — clear, practical, and role-specific:

----------

###  **M1 – Authentication Feature**

1.  Start from latest `main`:
    
    ```bash
    git checkout main && git pull origin main
    
    ```
    
2.  Create your branch:
    
    ```bash
    git checkout -b feature/john-auth
    
    ```
    
3.  Implement authentication logic (login, JWT, etc.).
    
4.  Commit regularly with clear messages.
    
5.  Push and open a PR to `main` (or `develop`).
    
6.  Request review from Amy and Sam.
    

----------

###  **M2 – Dashboard UI**

1.  Pull latest `main`:
    
    ```bash
    git checkout main && git pull origin main
    
    ```
    
2.  Create your branch:
    
    ```bash
    git checkout -b feature/amy-dashboard
    
    ```
    
3.  Build dashboard components and layout.
    
4.  Commit and push frequently.
    
5.  Open a PR and tag John or Lisa for review.
    
6.  Resolve feedback, then merge when approved.
    

----------

###  **M3 – API Integration**

1.  Sync with `main`:
    
    ```bash
    git checkout main && git pull origin main
    
    ```
    
2.  Create your branch:
    
    ```bash
    git checkout -b feature/sam-api
    
    ```
    
3.  Implement API calls and connect backend endpoints.
    
4.  Test locally and commit changes.
    
5.  Push and open a PR — assign John for testing integration.
    
6.  After review, merge and delete your branch.
    

----------

###  **M4 – Reporting & Analytics**

1.  Update local main:
    
    ```bash
    git checkout main && git pull origin main
    
    ```
    
2.  Create branch:
    
    ```bash
    git checkout -b feature/lisa-reports
    
    ```
    
3.  Add reporting/analytics components.
    
4.  Test data connections; commit changes.
    
5.  Push to remote and open PR.
    
6.  Request Amy or Sam for review, merge after approval.
    

----------

### 🧩 Common Rules for Everyone

-   **Never commit directly to `main`.**
    
-   **Keep branches small and focused.**
    
-   **Pull from `main` daily** to avoid conflicts.
    
-   **Use clear commit messages:**  
    e.g. `git commit -m "Add login validation on frontend"`
    
-   **Delete your branch** after merge.
    

----------