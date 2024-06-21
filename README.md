# 🌊 My portfolio

![Frame](https://raw.githubusercontent.com/vsantos1711/portfolio/main/public/assets/project-example.png)

## Project Status

![Status](https://img.shields.io/static/v1?label=STATUS&message=IN%20PROGRESS&color=blue&style=for-the-badge)

> [!IMPORTANT]
> Since the application is still under development, please note that topics not yet completed will be highlighted by a message like that

## Description

Welcome to my personal portfolio, a platform built with Next.js and TailwindCSS, specifically designed for developers who want to showcase their work in a dynamic and 100% integrated way with GitHub.

#### Main features:

- **Direct Connection with GitHub:** All my posts and projects are linked to my GitHub repositories. Any updates made to my repositories will automatically be reflected in the portfolio.
- **Dynamic Portfolio/Blog:** Each repository becomes a post on my portfolio/blog. Information is extracted directly from the README.md files of my repositories, displaying details about projects, challenges, and studies.
- **"About Me" and "CV" Sections:** Includes an "About Me" section where you can learn more about me, and a "CV" section where you can view my skills and experiences!
- **No Database or API:** No database or API needed. All content displayed on the website is hosted directly on GitHub, eliminating the need for additional databases or APIs. Simple and efficient!

## Technologies Used

- **[Next.js:](https://nextjs.org/)** The React framework used to build the portfolio, providing server-side rendering and static site generation.
- **[TypeScript:](https://www.typescriptlang.org/)** The primary programming language for the project, ensuring type safety and enhancing code quality.
- **[TailwindCSS:](https://tailwindcss.com/)** Utility-first CSS framework used for styling the portfolio quickly and efficiently.
- **[Vercel:](https://vercel.com/)** Platform used to host the portfolio, providing seamless deployment and serverless functions.
- **[GitHub:](https://github.com/)** Version control system used to fetch and display data directly from repositories, keeping the portfolio content updated.

## Usage

> [!IMPORTANT]
> We are currently assessing the need for standardizing the README.md files of projects so that they can be read by the application...

> To start using our app, you need to make some changes and follow standard README.md formatting, which can be found [here](https://github.com/vsantos1711/useful-things)

## Development

If you like and want to customize your own portfolio, you can run the application locally for code generation purposes or contributions. Follow the steps below to get started

<details open><summary> Pre-requisites </summary> <br />
To be able to start development the application make sure that you have the following pre-requisites installed:

- Pnpm
  ```bash
  npm install -g pnpm
  ```
- Node.js (versão LTS)

---
</details>

<details open><summary> Running the app </summary> <br />
To setup a local development environment the following steps can be followed:

1. Clone the repository and install dependencies:

```bash
git clone https://github.com/vsantos1711/portfolio.git && cd portfolio && pnpm install
```

2. Change the env file :

```
rename the .evn.example to .env
change the GITHUB_USER value to your user
```

3. Run the app:

```bash
pnpm run dev
```

</details>

## To-do

- [ ] Add syntax highlight
- [ ] Create a global state using [zustand](https://zustand-demo.pmnd.rs/)
- [ ] Create CV page
- [ ] Create "About me" page
- [ ] Add internationalization

## License

Licensed under the [MIT license](https://github.com/vsantos1711/portfolio/blob/main/LICENSE.md).
