# OpenStore maintainers

The list of developers on OpenStore: [`maintainers.yaml`](maintainers.yaml), one public GitHub repo per developer.

## Join

1. Create your listing repo from the **[template](https://github.com/p32929/openstore_template)** (*Use this template*), add your apps, and check them with `node validate.mjs`.
2. Open a pull request here adding your repo at the end of [`maintainers.yaml`](maintainers.yaml):

   ```yaml
   - your-github-name/your-repo
   ```

Your pull request is checked automatically: the line must be a GitHub repo, your account can't already be listed, your repo must be public and pass every OpenStore check, and the pull request must come from the repo's owner. Fix anything it reports in your own repo and the check re-runs when you push to the pull request.

That's the only time you come here. Everything else happens in your own repo.
