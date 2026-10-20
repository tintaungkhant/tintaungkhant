# Profile credits

This profile combines established community tools with descriptions drawn from my own work.

| Component | Source | Use |
| --- | --- | --- |
| Banner | [Capsule Render](https://github.com/kyechan99/capsule-render) | Generated blue wave banner, saved locally. |
| Technology icons | [Skill Icons](https://github.com/tandpfun/skill-icons) | Generated light and dark icon strips, saved locally. |
| Contribution summary | [GitHub Profile Summary Cards](https://github.com/vn7n24fzkq/github-profile-summary-cards) | Light and dark profile cards, refreshed by the existing workflow. |
| Layout inspiration | [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1), [Adam Alston](https://github.com/adamalston/adamalston) | Project-first organization, centered introduction, and theme-aware pictures. No personal copy or artwork taken. |
| Discovery | [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme), [GitHub topic](https://github.com/topics/github-profile-readme) | Community examples and reusable tools. |

## Assets and licenses

Generated SVGs are committed so visitors do not need third-party rendering services to load the profile. Their MIT notices are retained:

- [Capsule Render license](assets/reused/capsule-render.LICENSE)
- [Skill Icons license](assets/reused/skill-icons.LICENSE)
- [Summary Cards license](assets/reused/summary-cards.LICENSE)

Technology names and logos belong to their respective owners.

## Refreshing the profile

The existing `.github/workflows/profile-widgets.yml` runs daily and supports manual dispatch. It refreshes both `profile-summary-card-output/github/0-profile-details.svg` and `profile-summary-card-output/github_dark/0-profile-details.svg`. GitHub Actions needs permission to write repository contents. The committed cards provide an initial snapshot; the workflow refreshes them after publication. The optional `SUMMARY_GITHUB_TOKEN` secret is supported by that workflow; none is needed for the public-only initial cards.

Static asset generation URLs:

- [Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:174ea6,100:58a6ff&height=220&section=header&text=Tint%20Aung%20Khant&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Senior%20Backend%20Engineer%20%7C%20AI-First%20Software%20Engineer&descAlignY=57&descSize=16&animation=none)
- [Dark stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=dark)
- [Light stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=light)

Regenerate only when changing the design or stack. No custom rendering service or new dependency is required.

