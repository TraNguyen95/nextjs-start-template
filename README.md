

## How to Install and Get Started

1. **Essential Tools**: Ensure that [_VSCode_](https://code.visualstudio.com), [_Git_](https://learn.microsoft.com/en-us/devops/develop/git/install-and-set-up-git), _GitHub Desktop_ ([Windows/macOS](https://desktop.github.com) | [Linux](https://dev.to/rahedmir/is-github-desktop-available-for-gnu-linux-4a69)), _Node.js LTS_ ([Windows/macOS](https://nodejs.org) | [Linux](https://youtu.be/NS3aTgKztis)), and [_PNPM_](https://pnpm.io/installation) are installed.
2. **Project Cloning**: [_Create a new fork_](https://github.com/blefnk/relivator/fork) and use GitHub Desktop to download it.
3. **Configuration**: Open VSCode and load the project folder. Press `Ctrl+Shift+P` and search for `>Create New Terminal`. Enter `pnpm install` to install the packages. Next, copy the `.env.example` file to a new `.env` file and fill in at least the `NEXT_PUBLIC_DB_PROVIDER` and `DATABASE_URL` fields. Finally, send the database schema to your database using `pnpm mysql:push` or `pnpm pg:push`.
4. **Run, Stop, Build**: Use `pnpm dev` to run the app (visit <http://localhost:3000> to check it). Stop it by focusing on the console and pressing `Ctrl+C`. After making changes, build the app using `pnpm build`. _Thats okay if you see Clerk's warnings_ when executing `pnpm build`, this is a known issue not related to Relivator.
5. **Commit and Deploy**: Upload your project to your GitHub profile using GitHub Desktop. Then, deploy it by importing the project into [Vercel](https://vercel.com/new), making your website publicly accessible on the internet. If you wish to share your work, seek feedback, or ask for assistance, you're welcome to do so either [in our Discord server](https://discord.gg/Pb8uKbwpsJ) or [via GitHub discussions](https://github.com/blefnk/relivator/discussions).

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fblefnk%2Frelivator&project-name=relivator&repository-name=relivator)

Tip! You can create a folder, for instance, `home`, within the `src` directory, to store your project-specific files. It allows you for easy updates whenever Relivator has new versions.

> 🚀 **Ready to launch?** Start building your project with Relivator today!
