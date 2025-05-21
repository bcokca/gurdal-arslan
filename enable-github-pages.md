# How to Enable GitHub Pages for Your Repository

GitHub Pages allows you to host a static website directly from your GitHub repository. Follow these step-by-step instructions to enable GitHub Pages:

1.  **Go to Your GitHub Repository:**
    *   Open your web browser and navigate to [GitHub](https://github.com).
    *   Sign in to your account.
    *   Go to the repository for which you want to enable GitHub Pages.

2.  **Navigate to the "Settings" Tab:**
    *   On your repository's main page, look for the tabs at the top (e.g., "Code", "Issues", "Pull requests").
    *   Click on the "Settings" tab.

3.  **Go to the "Pages" Section:**
    *   In the "Settings" sidebar (usually on the left), find the "Code and automation" section.
    *   Click on "Pages" within this section.

4.  **Configure Build and Deployment Source:**
    *   Under the "Build and deployment" heading, you will see a "Source" option.
    *   Select "Deploy from a branch" from the dropdown menu. (This is often the default option).

5.  **Select the Branch and Folder:**
    *   Once "Deploy from a branch" is selected, a "Branch" section will appear or become active.
    *   **Branch:** Select your default branch from the dropdown. This is typically `main` or `master`.
    *   **Folder:** Ensure the folder is set to `/ (root)`. This means GitHub Pages will look for your site's `index.html` (or other entry point) in the root directory of your selected branch.

6.  **Save the Changes:**
    *   Click the "Save" button for the branch and folder selection.

**Important Notes:**

*   **Propagation Time:** After saving, it might take a few minutes for your GitHub Pages site to build and become active. GitHub will provide a URL for your live site (usually in the format `https://<your-username>.github.io/<repository-name>/`) on the same "Pages" settings page. You might need to refresh the page after a few minutes to see the URL.
*   **`index.html`:** For your site to be visible, you typically need an `index.html` file in the root of the branch you selected. If you don't have one, create it with your website content.
*   **Custom Domains:** GitHub Pages also supports custom domains, which you can configure later if needed.

That's it! Your repository should now be set up to deploy a website using GitHub Pages.
