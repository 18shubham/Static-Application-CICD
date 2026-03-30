Static Site CI/CD with GitHub Actions
This project demonstrates a foundational Continuous Integration and Continuous Deployment (CI/CD) pipeline. It automates the testing and deployment of a static HTML site to GitHub Pages.

🏗️ Architecture
The pipeline follows a standard DevOps lifecycle:

Code: Developer pushes changes to the main branch.

Build (CI): A GitHub-hosted Ubuntu runner environment is initialized.

Test (CI): Automated scripts verify the existence and content of index.html.

Deploy (CD): The validated code is bundled and hosted on GitHub Pages.


Shutterstock
Explore
🛠️ Tech Stack
Version Control: GitHub

Automation: GitHub Actions (YAML)

Environment: Ubuntu Latest (Managed Runner)

Hosting: GitHub Pages

Build Tooling: Node.js & NPM

📂 Project Structure

├── .github/workflows/
│   └── deploy.yml    # The CI/CD "Recipe"
├── dist/             # Generated production folder (ignored by Git)
├── index.html        # Main website file
└── package.json      # Build script configuration



