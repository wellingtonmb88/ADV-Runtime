# Awesome Advanced SVM Cohort Project Collection

This repository serves as a curated collection of projects created by participants of the Advanced SVM Cohort, a program focused on building applications using the Solana SVM (Scalable Virtual Machine) API. These projects were either fully developed during the cohort or started during the cohort and expanded afterward. Each entry links to the student's GitHub repository.


## Project List

- **Rust solana client extension:**
  - **Description**: A solana rust client extension crate can be used to simulate transactions locally using the SVM api.
  - **Status**: Completed during cohort.
  - **Demo**: [Link to live demo if available]
  - **Tech Stack**: Solana SVM API, Rust.

- **Based Rollup:**
  - **Description**: A single app rollup, using the SVM api.
  - **Status**: Completed during cohort.
  - **Demo**: [Link to live demo if available]
  - **Tech Stack**: Solana SVM API, Rust.

- **Custom Syscall:**
  - **Description**: A simple implementation of custom syscall. 
  - **Status**: Completed during cohort.
  - **Demo**: [Link to live demo if available]
  - **Tech Stack**: Solana SVM API, Solana SDK, Rust.

- **[Add more projects here...]**
  - **Description**: [Brief overview of the project and its purpose]
  - **Repo**: [Link to the student's GitHub repository]
  - **Status**: [Started during cohort or expanded afterward]
  - **Demo**: [Optional: Link to live demo or deployment]
  - **Tech Stack**: [List key technologies used]

## How to Contribute
We welcome contributions to add your project as a Git submodule! This allows the code to be included directly in this collection while linking back to your original repo.

To add or update a project:
1. Fork this repository on GitHub.
2. Clone your fork locally: `git clone https://github.com/Turbin3/ADV-Runtime.git`.
3. Add your project as a submodule:
   - Run `git submodule add <your-repo-url> <submodule-path>`.
   - Example: `git submodule add https://github.com/student/rollup student-rollup`.
   - Choose a clear path like `yourusername-projectname`.
4. Update the `README.md` file to include your project details in the **Project List** section, following the format above (include the submodule path).
5. Commit your changes: `git commit -am "Add submodule and README entry for my project"`.
6. Push to your fork: `git push`.
7. Submit a pull request to the main repository with a clear description of your addition.
8. Ensure your original repository is public (or grant access to the cohort organizer if private).

**Note**: Submodules point to specific commits in your repo. If you update your project later, you can submit another PR to update the submodule pointer.

## Contact
For questions or suggestions about this collection, reach out to the cohort organizer via berg@turbine.org.
