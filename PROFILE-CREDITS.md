# Profile credits

This profile combines established community tools with descriptions drawn from my own work.

| Component | Source | Use |
| --- | --- | --- |
| Banner | [Capsule Render](https://github.com/kyechan99/capsule-render) | Generated blue wave banner, saved locally. |
| Technology icons | [Skill Icons](https://github.com/tandpfun/skill-icons) | Generated light and dark icon strips, saved locally. |
| Contribution animation | [Platane/snk](https://github.com/Platane/snk) | Compact blue contribution snake in light and dark variants, refreshed daily. |
| Layout inspiration | [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1), [Adam Alston](https://github.com/adamalston/adamalston) | Project-first organization, centered introduction, and theme-aware pictures. No personal copy or artwork taken. |
| Discovery | [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme), [GitHub topic](https://github.com/topics/github-profile-readme) | Community examples and reusable tools. |

## Assets and licenses

Generated SVGs are committed so visitors do not need third-party rendering services to load the profile. Their MIT notices are retained:

- [Capsule Render license](assets/reused/capsule-render.LICENSE)
- [Skill Icons license](assets/reused/skill-icons.LICENSE)
- [Summary Cards license](assets/reused/summary-cards.LICENSE)

Technology names and logos belong to their respective owners.

## Refreshing the profile

The existing `.github/workflows/profile-widgets.yml` runs daily and supports manual dispatch. The `Platane/snk/svg-only@v3` step refreshes `assets/contributions/snake-light.svg` and `assets/contributions/snake-dark.svg` from the repository owner's contribution calendar. GitHub Actions needs permission to write repository contents. Both animations are committed, so the profile works before the first scheduled run. The snake uses the built-in GitHub Actions token; no additional secret is required. The earlier summary-card and 3D generators remain in the workflow, but their output is no longer displayed in the README.

Static asset generation URLs:

- [Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:174ea6,100:58a6ff&height=220&section=header&text=Tint%20Aung%20Khant&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Senior%20Backend%20Engineer%20%7C%20AI-First%20Software%20Engineer&descAlignY=57&descSize=16&animation=none)
- [Dark stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=dark)
- [Light stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=light)

Regenerate only when changing the design or stack. No custom rendering service or new dependency is required.

