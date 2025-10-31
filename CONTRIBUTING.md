# Contributing to PPCC25-RD

Thank you for your interest in contributing to the Power Platform Community Conference 2025 Repository!

## How to Contribute

This repository contains interactive posters for the Community Lounge at the Power Platform Community Conference. Contributions are welcome for improvements, corrections, or updates to the poster content.

## Adding Collaborators to Act on Pull Requests

### For Repository Administrators

If you need to add collaborators who can review, approve, and merge pull requests, follow these steps:

#### Option 1: Add Individual Collaborators

1. Navigate to the repository on GitHub: `https://github.com/microsoft/PPCC25-RD` (or your repository URL)
2. Click on **Settings** (you need admin access to see this)
3. In the left sidebar, click **Collaborators and teams**
4. Click **Add people** or **Add teams**
5. Search for the GitHub username or team name
6. Select the appropriate permission level:
   - **Read**: Can view and clone the repository
   - **Triage**: Can manage issues and pull requests without writing access
   - **Write**: Can push to the repository and manage issues/PRs
   - **Maintain**: Can manage the repository without access to sensitive actions
   - **Admin**: Full access to the repository
7. Click **Add [username/team] to this repository**

#### Option 2: Use GitHub Teams

For organization repositories, it's recommended to use Teams for better management:

1. Go to your organization's page: `https://github.com/microsoft` (or your organization URL)
2. Click on **Teams**
3. Create a new team or select an existing one
4. Add members to the team
5. Go back to the repository Settings → Collaborators and teams
6. Add the team with the appropriate permission level

#### Option 3: Configure CODEOWNERS File

The repository includes a `.github/CODEOWNERS` file that automatically requests reviews from specific users or teams:

1. Edit the `.github/CODEOWNERS` file
2. Replace `@microsoft/ppcc25-organizers` with your actual team name or individual usernames
3. You can specify different owners for different file types
4. Commit and push the changes

This ensures that the right people are automatically notified when pull requests are opened.

### For Pull Request Reviewers

Once added as a collaborator with **Write** access or higher, you can:

- Review pull requests
- Approve or request changes
- Merge pull requests (if you have write access)
- Close pull requests
- Assign reviewers and labels

### Pull Request Workflow

1. **Creating a Pull Request**
   - Fork the repository or create a branch
   - Make your changes
   - Submit a pull request with a clear description
   - Reference any related issues

2. **Reviewing a Pull Request**
   - Check that the changes align with the project goals
   - Verify that the changes don't break existing functionality
   - Provide constructive feedback
   - Approve the PR if it meets the standards

3. **Merging a Pull Request**
   - Ensure all required reviews are complete
   - Check that all CI/CD checks pass (if applicable)
   - Use "Squash and merge" for cleaner history (recommended)
   - Delete the branch after merging

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Getting Help

If you need help or have questions:
- File an issue in this repository
- Contact: jal@microsoft.com

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (see [LICENSE](LICENSE) file).
