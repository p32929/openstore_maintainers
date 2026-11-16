<h1 align="center">OpenStore maintainers</h1>
<p align="center"><b>The list of developers on <a href="https://openstore.pfay.workers.dev">OpenStore</a>.</b><br>
Add one line, open one pull request, and your apps are in the store.</p>
<p align="center"><a href="https://openstore.pfay.workers.dev"><b>See the store →</b></a> &nbsp;·&nbsp; <a href="https://openstore.pfay.workers.dev/add">Step-by-step guide</a> &nbsp;·&nbsp; <a href="https://openstore.pfay.workers.dev/why">Why OpenStore</a></p>

<p align="center">
  <a href="https://openstore.pfay.workers.dev"><img src="docs/store-desktop.png" alt="OpenStore on desktop" width="68%"></a>
  <a href="https://openstore.pfay.workers.dev"><img src="docs/store-mobile.png" alt="OpenStore on mobile" width="22%"></a>
</p>

## What is OpenStore?

An open app store where **you** keep your listing: a few text files in your own public GitHub repo. No fees, no testers, no approval wait, and nobody can remove your apps. Add web apps, Android and iOS apps, desktop apps and libraries, all in one place.

This repo is the list of who is on it: [`maintainers.yaml`](maintainers.yaml), one repo per developer.

## Join in 4 steps

1. **Make your listing repo.** Download or clone the [template](https://github.com/p32929/p32929_openstore/tree/template) into a new **public** repo.
2. **Add your apps.** One `.md` file per app in `apps/`.
3. **Check it.** Run `node validate.mjs`, or paste your repo at [openstore.pfay.workers.dev/validate](https://openstore.pfay.workers.dev/validate).
4. **Open a pull request here** that adds one line at the end of [`maintainers.yaml`](maintainers.yaml):

   ```yaml
   - your-github-name/your-repo
   ```

That is the only time you come here. After this, you just push to your own repo.

## What gets checked

Your pull request is checked automatically:

1. The line is a GitHub repo.
2. Your account is not already listed.
3. Your repo is public and passes every OpenStore check.
4. The pull request comes from the owner of the repo.

If something fails, the check says what. Fix it in your own repo and push; the check runs again.

## Questions?

Ask in [OpenStore feedback](https://github.com/p32929/openstore_feedback): Issues for bugs and ideas, Discussions for everything else.

## Contributing

To join the store, the pull request described above is all you need, no issue required. For anything else, like a change to the checks or to this page, please open an issue first and tell me what you have in mind. That way we can agree on it before you spend time on a pull request. Thank you!

## Share

<a href="https://p32929.github.io/share/?repo=openstore_maintainers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/share-dark.svg"><img src="https://p32929.github.io/readme/share-light.svg" alt="Share this with your friends in just a click" width="420"></picture></a>

## Support

<a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/support-dark.svg"><img src="https://p32929.github.io/readme/support-light.svg" alt="If you like my works and want to support me, feel free to support" width="420"></picture></a>
