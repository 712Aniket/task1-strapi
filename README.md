# Task-1: Strapi Setup

## Overview
This project demonstrates running Strapi locally using npm and creating a sample content type.

## Setup Steps
1. Verified Node.js and npm installation
2. Created Strapi app using:
   npx create-strapi-app@latest . --quickstart
3. Started Strapi using:
   npm run develop
4. Accessed Admin Panel at:
   http://localhost:1337/admin
5. Created a sample content type "Article" with fields:
   - title
   - description
   - publishedDate
6. Added a sample entry

## Tools Used
- Node.js v20
- npm
- Strapi v5

## Loom Video
<PASTE YOUR LOOM LINK HERE>

## Pull Request
This PR contains the complete setup for Task-1 using a feature branch `aniket`.


## Challenges Faced & How They Were Solved

### 1. Package Manager Compatibility
Initially, the Strapi core repository was cloned as per the instruction. However, it was identified that the Strapi core repository is a Yarn-based monorepo and does not support npm for dependency installation.

**Solution:**  
Since the requirement was to use npm, the approach was adjusted to create a Strapi application using `npx create-strapi-app`, which is the recommended and production-ready way to use Strapi with npm.

---

### 2. Repository Ownership & Pull Request Flow
At the beginning, a pull request was mistakenly created against the official Strapi repository instead of a personal GitHub repository.

**Solution:**  
A new public repository was created under my GitHub account. The project was pushed to this repository, a separate feature branch (`aniket`) was created, and a pull request was raised from this branch to the main branch, following the correct Git workflow.

---

### 3. Local Environment & Folder Structure Issues
While setting up the project on Windows with WSL, there were issues related to folder structure, locked directories, and non-empty directories during setup.

**Solution:**  
The workspace was cleaned, directories were reset properly, and the project was recreated in a clean folder. This ensured a stable local development environment and avoided conflicts during setup.


