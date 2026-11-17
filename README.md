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

## You might also like

<a href="https://openstore.pfay.workers.dev/cards/p32929?n=4&amp;repo=openstore_maintainers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929.svg?n=4&amp;repo=openstore_maintainers&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929.svg?n=4&amp;repo=openstore_maintainers&amp;theme=light" width="100%" alt="More apps by p32929 on OpenStore"></picture></a>

<p><a href="https://p32929.github.io/share/?repo=openstore_maintainers"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
