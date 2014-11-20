Result visible at this address: `http://`*`username`*`.github.io/svg-to-font/`.
For example: http://cr0ck.github.io/svg-to-font/.

Deployment instructions for `gh-pages` from http://yeoman.io/learning/deployment.html:

> ## Git subtree command
> 
> You can also maintain the source and built code on the same branch, and deploy only the `dist` directory with the [`git subtree`](https://github.com/apenwarr/git-subtree) command.
> 
> 1. Remove the `dist` directory from the `.gitignore` file. Yeoman projects ignore it by default.
> 2. Add the `dist` directory to your repository:
> 
>         git add dist && git commit -m "Initial dist subtree commit"
> 
> 3. Deploy the subtree to a different branch. Specify a relative path to your `dist` directory with `--prefix`:
> 
>         git subtree push --prefix dist origin gh-pages
> 
> 4. Develop normally, committing your entire repository to your default (master) branch.
> 5. To deploy the `dist` directory, run the `subtree push` command from the root directory:
> 
>         git subtree push --prefix dist origin gh-pages
