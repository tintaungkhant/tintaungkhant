# Profile credits

This profile combines established community tools with descriptions drawn from my own work.

| Component | Source | Use |
| --- | --- | --- |
| Banner | [Capsule Render](https://github.com/kyechan99/capsule-render) | Generated blue wave banner, saved locally. |
| Technology icons | [Skill Icons](https://github.com/tandpfun/skill-icons) | Generated light and dark icon strips, saved locally. |
| Contribution animation | [GitHub Gravity](https://github.com/flycran/github-gravity) | Real active contribution days fall and bounce around my name. Reuses its physics renderer with blue palettes and a repeating animation. |
| Layout inspiration | [DenverCoder1](https://github.com/DenverCoder1/DenverCoder1), [Adam Alston](https://github.com/adamalston/adamalston) | Project-first organization, centered introduction, and theme-aware pictures. No personal copy or artwork taken. |
| Discovery | [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme), [GitHub topic](https://github.com/topics/github-profile-readme) | Community examples and reusable tools. |

## Assets and licenses

Generated SVGs are committed so visitors do not need third-party rendering services to load the profile. Their MIT notices are retained:

- [Capsule Render license](assets/reused/capsule-render.LICENSE)
- [Skill Icons license](assets/reused/skill-icons.LICENSE)
- [Summary Cards license](assets/reused/summary-cards.LICENSE)
- [GitHub Gravity license](assets/reused/github-gravity.LICENSE)

Technology names and logos belong to their respective owners.

## Refreshing the profile

The existing `.github/workflows/profile-widgets.yml` runs daily and supports manual dispatch. `flycran/github-gravity@v1` reads the public contribution calendar through its upstream `gh-calendar.rschristian.dev` provider and simulates the falling dots. Each dot represents an active day, and its color represents the contribution intensity; this is an artistic view, not a chronological chart after the dots fall.

`scripts/finalize-gravity.mjs` keeps the upstream trajectories and data, adds continuous looping, and writes local light and dark SVG variants. Reduced-motion preferences show a still frame. Committed SVGs load before the first scheduled run, and no extra secret is required. The workflow only generates the contribution animation displayed in the README.

I found Gravity in the curated list's Tools section. Other options reviewed included [Git Bonsai](https://github.com/egorthinks/git-bonsai), which grows a pixel tree from account history, and the list's interactive game profiles. Gravity keeps daily contribution data visible while adding substantial motion directly inside a README image.

Static asset generation URLs:

- [Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:174ea6,100:58a6ff&height=220&section=header&text=Tint%20Aung%20Khant&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Senior%20Backend%20Engineer%20%7C%20AI-First%20Software%20Engineer&descAlignY=57&descSize=16&animation=none)
- [Dark stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=dark)
- [Light stack](https://skillicons.dev/icons?i=php,laravel,ts,nodejs,postgres,mysql,redis,go,docker,aws&perline=10&theme=light)

Regenerate only when changing the design or stack. No custom rendering service or new dependency is required.

