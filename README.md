# PE08 – Static Web App Deployment

**Student:** Dat Tran  
**Course:** CS445 – Web Programming  
**Exercise:** Programming Exercise 08 – Azure Static Web Apps

---

## ❓ Questions & Responses

### 1. What commands/options did you use to get the `index.html` file from the `dev1` branch to the `main` branch?

To integrate the `index.html` file into the main branch, I used the following steps:

- Created a new branch using `git checkout -b dev1`
- Added and committed `index.html` in the `dev1` branch
- Pushed the branch with `git push origin dev1`
- On GitHub, I created a pull request and merged `dev1` into `main` using the “Merge pull request” option.

This triggered an automated deployment via GitHub Actions.

---

### 2. How long did the Build and Deploy take?

The deployment process took approximately **1 minute and 15 seconds**, based on the GitHub Actions logs. This included time for build, staging, and deployment to the Azure Static Web App endpoint after the pull request was merged.

---

### 3. What is displayed when you click on the ‘Click Me!’ button?

When the **“Click me!”** button is clicked on the deployed page, the following output appears:

