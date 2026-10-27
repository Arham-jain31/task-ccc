# SIT313 C1 – New Post Page (Beginner Version)

This project extends the existing DEV@Deakin React website from the supplied P3/P4 project. The code is kept simple and uses basic React components and `useState`.

## C1 features

- Added a New Post page at `/post`.
- The Post button in the navigation opens the New Post page.
- The user can select Question or Article.
- The form changes based on the selected post type (conditional rendering).
- Question fields: title, problem description and tags.
- Article fields: title, abstract, article text and tags.
- Basic validation checks that required fields are filled in.
- Tags are separated by commas and limited to 3 tags.
- The Post button shows a popup after validation. This task does not save posts to a database, as the C1 brief says posting functionality will be implemented in a future task.

## Run the project

1. Open this folder in VS Code.
2. Open the terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local address shown in the terminal.

## Important

- Do not upload `node_modules` or your `.env` file to GitLab.
- Keep the repository visibility set to Internal as required by the task sheet.
- Commit your code and resources to the C1 repository.
- The task sheet also asks for screenshots, a 2–4 minute Panopto walkthrough video, and a short report containing your GitLab and video links.

## Main new/updated files

- `src/pages/Post.jsx` – the beginner-level post form and validation.
- `src/App.jsx` – adds the `/post` route.
- `src/components/Header.jsx` – makes the Post button open the new page.
- `src/index.css` – styles the post form.
