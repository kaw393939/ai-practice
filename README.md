# Working with AI

Practice one small change: **add help text below the Note box** in a working link-saving app. Learn to describe a change, discuss a plan, review AI edits, and check the result.

Use **ChatGPT desktop, Codex, and VS Code**. No OpenAI API key is needed.

## Start here

1. On [the starter repository](https://github.com/kaw393939/218_spec), choose **Use this template → Create a new repository**. Select your account, name it `ai-practice`, choose **Public**, and leave **Include all branches** unchecked.
2. Open your class terminal in the folder where you keep projects. Replace `YOUR-USERNAME` with your GitHub username, then run:

   ```sh
   git clone https://github.com/YOUR-USERNAME/ai-practice.git
   cd ai-practice
   pwd
   git remote -v
   ```

   `origin` should point to your repository. Open this same folder in VS Code to read and edit files.
3. Follow [Setup](https://kaw393939.github.io/218_spec/setup.html) to run the app and check access.
4. Follow [Your first change](https://kaw393939.github.io/218_spec/practice.html): discuss → issue → AI edit → check → pull request.

**Create your copy on GitHub, then clone that copy to your computer.** Your issues and PRs belong in your own repository. **Already have your GitHub copy?** Start at step 2. **Already have the local folder?** Start at step 3; keep using that folder.

## What you start with

- `main` contains the working app and the unfinished **PRACTICE-001** spec. The new help sentence should be absent.
- `docs/specs/practice.md` describes your task; `app/public/index.html` is the file you will change.
- The [completed LINK-001 example](https://kaw393939.github.io/218_spec/example.html) is background, not another task to implement.

The [instructions site](https://kaw393939.github.io/218_spec/) serves documentation. Run the app locally with `npm ci`, then `npm start`; open the address printed in the terminal. Use Node.js 24 (22.13 or newer works).

Your copy runs build checks but does **not** publish a website. Only this instructor repository publishes GitHub Pages. Website maintenance instructions are in [Maintaining this website](docs/contributing.md).
