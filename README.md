# web-devdelopment-workflow
# Modern Web Development Workflow

```mermaid
flowchart LR

A[Local Git Repository<br>HTML, CSS, JavaScript<br>PHP, Python, Node.js] 
--> B[GitHub / GitLab / Bitbucket]

A --> C[MySQL / PostgreSQL<br>Local Database]

B --> D[CI/CD<br>Testing & Linting]

D --> E[Hosting<br>Website + Database]

A --> F[FTP]

F --> E

E --> G[Domain & DNS]

G --> H[Web Browser]
