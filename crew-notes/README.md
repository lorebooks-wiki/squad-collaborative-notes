# Welcome aboard!

This is our (public) collaborative notes repository between the squad members in Markdown. If you need a private place to take down notes with
a squad members, just grab a copy of this repo as a private fork on your own and invite along.

## Getting started

1. Request write access by [completing the onboarding workflow for squad members](https://onboard.lorebooks.eu.org/squad)[^1]. Expect up to 7 days
to process your request and invite you to `@lorebooks/squad` team (Not receiving the invitation email? [Try opening this link](https://github.com/orgs/Community-Lores/invitations)).
3. Add a new workspace in [StackEdit+](https://stackedit.net/app) by going to **Workspaces** -> **Add GitHub workspace**.
    * URL: `https://github.com/Community-Lores/squad-collaborative-notes`
    * Branch: `username/<your-branch-name` OR `main` (once you're preapproved by a squad member per branch protection/rule settings).
    * Directory: `crew-notes`[^2]
4. (Re)authenticate with GitHub and happy editing!

## Troubleshooting + Docs

### Help! I got ratelimited faster on GitHub. How do I configure automatic synchorization delay?

Change `autoSyncEvery` in Settings into something like `300000` (yes, that's 5 minutes in millseconds) and save.

```yaml
autoSyncEvery: 300000 # 5 minutes
```

[^1]: Anybody else can ask for write access to non-protected branches via [this repo's issue tracker](https://github.com/Community-Lores/squad-collaborative-notes/issues).
[^2]: Instead of messing up with files on the root directory, we do use a directory on this.
