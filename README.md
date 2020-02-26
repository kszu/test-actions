I'm going to use this repo to create a new GitHub Action 🎉

Ideally, this action will:
1) Trigger upon a new PR.
2) Check for a package.json file in the PR.
3) Check to see if there are any new dependencies introduced into the `package.json` or `package-lock.json` files.
4) If yes, alert the user in the PR that a new dependency was introduced via a label on the PR.
5) If no, do nothing.

That's it!
