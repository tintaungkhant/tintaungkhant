# Profile credits

This profile combines established community tools with descriptions drawn from my own work.

| Component | Source | Use |
| --- | --- | --- |
| Banner | [Capsule Render](https://github.com/kyechan99/capsule-render) | Generated blue wave banner, saved locally. |
| Technology icons | [Skill Icons](https://github.com/tandpfun/skill-icons) | Generated light and dark icon strips, saved locally. |
| Project status badges | [Shields.io](https://shields.io/) | Locally saved open-source, private, in-development, and pre-release badges. |
| Contribution animation | [GitHub Space Shooter](https://github.com/czl9707/gh-space-shooter) | A looping arcade GIF generated from my real GitHub contribution calendar. Contribution intensity determines enemy strength. |
| Layout inspiration | [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1), [Adam Alston](https://github.com/adamalston/adamalston) | Project-first organization, centered introduction, and theme-aware pictures. No personal copy or artwork taken. |
| Discovery | [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme), [GitHub topic](https://github.com/topics/github-profile-readme) | Community examples and reusable tools. |

## Assets and licenses

Generated images are committed so visitors do not need third-party rendering services to load the profile. Relevant MIT notices are retained:

- [Capsule Render license](assets/reused/capsule-render.LICENSE)
- [Skill Icons license](assets/reused/skill-icons.LICENSE)
- [Summary Cards license](assets/reused/summary-cards.LICENSE)
- [Space Shooter license](assets/reused/space-shooter.LICENSE)

Technology names and logos belong to their respective owners.

## Refreshing the profile

`.github/workflows/profile-widgets.yml` runs daily and supports manual dispatch. It uses the upstream Space Shooter action, pinned to commit `b24c9792454d1a2e0139ccf72840424e1f83c3f2`, to fetch the repository owner's contribution calendar and generate `assets/contributions/space-shooter.gif` at 25 fps with the random attack strategy.

The action uses the built-in GitHub Actions token and needs no additional secret. Its own commit behavior is disabled; the workflow's final step commits the generated asset without amending history. The committed GIF works before the first scheduled run. The image depicts actual contribution data as enemies, with an arcade animation rather than a chronological chart after gameplay starts.

For a local preview, install `gh-space-shooter` and run `gh-space-shooter tintaungkhant --output assets/contributions/space-shooter.gif --strategy random --fps 25` with `GH_TOKEN` supplied through the environment. Never commit the token.

Static asset generation URLs:

- [Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:174ea6,100:58a6ff&height=220&section=header&text=Tint%20Aung%20Khant&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Senior%20Backend%20Engineer%20%7C%20AI-First%20Software%20Engineer&descAlignY=57&descSize=16&animation=none)
- [Dark stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=dark)
- [Light stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=light)

Regenerate only when changing the design or stack. No custom rendering service or new dependency is required.

