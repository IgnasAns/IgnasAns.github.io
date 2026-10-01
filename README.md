# IgnasAns.github.io

The one place for every public web document of Ignas Anskaitis's apps and games: privacy
policies, store disclosures and their demo videos. Served by GitHub Pages at
https://ignasans.github.io/.

## Layout

One folder per app (or family of apps). The folder names are the names of the repositories
these documents used to live in, on purpose: every URL already entered in a Play Console
listing keeps working. **Do not rename a folder** without first changing the URL in the
Console, and never delete one whose app is still on a store.

| Folder | What it holds |
| --- | --- |
| `doitmate-legal/` | Do It Mate privacy policy (`index.html`; `PRIVACY_POLICY.md` is the same text) |
| `NutriValue-Legal/` | NutriValue privacy policy |
| `focuspulse-assets/` | FocusPulse privacy policy and disclosure video |
| `nosocial-assets/` | No Social privacy policy, accessibility and foreground-service videos |
| `parentshield-assets/` | ParentShield privacy policy |
| `minimalu-assets/`, `lockout-assets/`, `alarmquest-assets/` | Store disclosure and demo videos |
| `portfolio-policies/` | Policies for the utility app series (`com.ianskaitis.*`); `build.py` regenerates them from `privacy/template.html` |
| `privacy-policy/` | One policy for the ten IA Engineering offline games |
| `onetower-assets/`, `Ironvale-Legal/`, `heirloom-assets/`, `zombiefront-assets/`, `alchemysort-assets/` | Game privacy policies |

`app-ads.txt` at the root is the AdMob seller declaration and has to stay there.
`.nojekyll` makes Pages serve the files as they are.

## Adding a new app

1. Make a folder for it (a short lower-case name) with the policy as `index.html`.
2. Link it from `index.html` at the root.
3. Push to `main`; Pages redeploys in about a minute.
4. Open the URL, then paste it into the Play Console listing.

## Changing a policy

Edit the page here, bump the effective date, and update the in-app copy and the store
listing text if the data practices changed. The apps' own repositories keep source only;
they should link here instead of holding a copy.
