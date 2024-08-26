# Minimal Research Compendium Template

This repository is a minimal template for starting research projects. It provides the basic structure to help researchers organize their work, ensuring reproducibility and ease of collaboration. While the core principles are maintained, this template starts with only the essential files and leaves the creation of certain directories to the user.

## Repository Structure

- **DESCRIPTION**: Contains project metadata, including title, version, author, and a brief description of the project.
- **README.md**: Provides a top-level overview of the repository's contents and a guide for users.
- **.gitignore**: Specifies files and directories to be ignored by Git, ensuring that unnecessary or sensitive files are not included in the repository. The `data/` directory is included in the `.gitignore` by default to prevent the accidental sharing of sensitive data. This `.gitignore` file is tailored for R projects and may need adjustment based on your specific needs.

## Getting Started

1. **Clone the repository**: Start by cloning this repository to your local machine.
   ```bash
   git clone https://github.com/vljlangen/minimal-research-compendium-template.git
   ```
2. **Create the `data/` directory**: Manually create a `data/` directory to store raw data files. 
3. **Add your data**: Place your raw data files in the `data/` directory. Ensure that these files remain unchanged after their initial creation to preserve data integrity.
4. **Create the `analysis/` directory**: Manually create an `analysis/` directory to store your analysis scripts. All analyses should be run separately within this directory.
5. **Document your work**: Update the `README.md` and other documentation as your project progresses.
6. **Review the `.gitignore`**: Make sure the `.gitignore` file is set up to exclude any files you don’t want to track in Git. This file is configured for R projects, so adjust it as necessary for your specific project.

