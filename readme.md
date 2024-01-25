# GitHub Viewer

GitHub Viewer is a simple web application that enables users to explore GitHub repositories with ease. It provides features like filtering the number of repositories displayed per page, searching repositories by name, and jumping between pages within a specified range.

## Features

### 1. Repo Per Page Filtering
Easily adjust the number of repositories displayed per page to suit your preferences. This feature provides a customizable viewing experience.

### 2. Page Jumps in Range
Navigate through a specific range of pages quickly. GitHub Viewer allows you to jump between pages within a specified range for efficient exploration.

### 3. Search on Repo Name
Effortlessly find repositories by searching for their names. The search functionality helps you locate specific repositories based on your criteria.

## Screenshots

1. **Changed Repo Per Page**
   ![Changed Repo Per Page](./images/changed-repo-per-page.png)

2. **GitHub Viewer on Basis of Search Filter**
   ![GitHub Viewer on Basis of Search Filter](./images/github-viewer-search-filter.png)

3. **Default**
   ![Default](./images/default.png)

4. **Random Set of Page + Random Page**
   ![Random Set of Page + Random Page](./images/random-set-of-page-random-page.png)

## Technologies Used
- JavaScript
- HTML
- Bootstrap CSS

## Getting Started

To run the GitHub Viewer locally and access GitHub data, follow these steps:

1. **Generate GitHub Personal Access Token:**
   - Visit [GitHub Personal Access Tokens](https://github.com/settings/tokens) and generate a new token with the necessary permissions.
   - Copy the generated token.

2. **Locate `script.js` file:**
   - Open the `script.js` file in the `js` folder of your project.

3. **Update API Key and Username:**
   - Find the following lines in the `script.js` file:
     ```javascript
     const apiKey = "Put your GitHub API key";
     const username = "Put the GitHub username you want to view";
     ```
   - Replace `"Put your GitHub API key"` with your generated GitHub Personal Access Token.
   - Replace `"Put the GitHub username you want to view"` with the GitHub username whose repositories you want to view.

4. **Save Changes:**
   - Save the changes to the `script.js` file.

Now you're ready to run the GitHub Viewer with your own API key and specified GitHub username.

![Api Key and username location in script.js](./images/api-key-and-username-location-in-script.png)

## Live Demo

Access the live demo of GitHub Viewer hosted on [Cyclic](https://pear-quaint-colt.cyclic.app).

