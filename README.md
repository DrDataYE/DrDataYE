👨‍💻 DrDataYE - Programmer | Developer | Cybersecurity Expert 👨‍💻

Welcome to my GitHub profile! I'm DrDataYE, a passionate programmer and skilled developer with a focus on creating innovative solutions. With a strong background in cybersecurity, I'm dedicated to building robust and secure software.

🌐 Web | 📱 App | 💻 Software | 🔒 Cybersecurity

🔭 Exploring new technologies and pushing the boundaries of what's possible.
🧠 Crafting elegant code while ensuring top-notch security measures.
💡 Transforming ideas into functional and user-friendly applications.
🌟 Constantly learning and staying updated in the ever-evolving tech landscape.

Connect with me to collaborate on exciting projects, discuss cybersecurity strategies, and dive into the world of coding. Let's make the digital realm safer and more efficient together!

Get in touch:
💬 Telegram: [MyTelegram](https://t.me/DrdataYE)
🌐 Website: www.cyber1101.com


<!---
DrDataYE/DrDataYE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


[![Stand With Palestine](https://raw.githubusercontent.com/TheBSD/StandWithPalestine/main/banner-no-action.svg)](https://TheBSD.github.io/StandWithPalestine/)

<a align='center' href=''>
    <p align="center">
        <img width='100%' src='https://github.com/muath-ye/muath-ye/raw/master/img/banner.svg' />
    </p>
</a>

<a align='center' href=''>
    <p align="center">
        <img width='100%' src='https://wakatime.com/share/@muathye/a8930a67-96a2-428a-9d1b-bf362372e755.svg' />
    </p>
</a>

<!-- 2022 10 27 | 12:02 - 12000 -->
<p align="center">
    <img src="https://komarev.com/ghpvc/?username=DrDataYE&label=221,027|1202&color=0e75b6&style=flat" alt="Muathye" />
    <img src="https://wakatime.com/badge/user/caa98403-bf58-4655-a14f-0e8425d6225b.svg" alt="Total time coded since May 26 2022" />
</p>



<details align="center">
<summary> <b> <samp> My Profile 🟡 </samp></b></summary>
# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          #  - public_repo
          #  - read:project
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          user: DrDataYE
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Africa/Khartoum
          plugin_achievements: yes
          plugin_achievements_display: detailed
          plugin_achievements_secrets: yes
          plugin_achievements_threshold: C
          plugin_anilist: yes
          plugin_anilist_limit: 2
          plugin_anilist_limit_characters: 22
          plugin_anilist_medias: anime, manga
          plugin_anilist_sections: favorites
          plugin_anilist_shuffle: yes
          plugin_anilist_user: .user.login
          plugin_calendar: yes
          plugin_calendar_limit: 1
          plugin_discussions: yes
          plugin_discussions_categories: yes
          plugin_habits: yes
          plugin_habits_charts_type: classic
          plugin_habits_days: 14
          plugin_habits_facts: yes
          plugin_habits_from: 200
          plugin_habits_languages_limit: 8
          plugin_habits_languages_threshold: 0%
          plugin_introduction: yes
          plugin_introduction_title: yes
          plugin_languages: yes
          plugin_languages_analysis_timeout: 15
          plugin_languages_analysis_timeout_repositories: 7.5
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
          plugin_lines: yes
          plugin_lines_history_limit: 1
          plugin_lines_repositories_limit: 4
          plugin_lines_sections: base
          plugin_music: yes
          plugin_music_limit: 4
          plugin_music_time_range: short
          plugin_music_top_type: tracks
          plugin_music_user: .user.login
          plugin_notable: yes
          plugin_notable_from: organization
          plugin_notable_types: commit
          plugin_pagespeed: yes
          plugin_pagespeed_url: .user.website
          plugin_posts: yes
          plugin_posts_limit: 4
          plugin_posts_user: .user.login
          plugin_projects: yes
          plugin_projects_limit: 4
          plugin_screenshot: yes
          plugin_screenshot_background: yes
          plugin_screenshot_mode: image
          plugin_screenshot_selector: body
          plugin_screenshot_title: Screenshot
          plugin_screenshot_url: https://www.cyber1101.com
          plugin_screenshot_viewport: {
  "width": 1280,
  "height": 1280
}

          plugin_skyline: yes
          plugin_skyline_frames: 60
          plugin_skyline_quality: 0.5
          plugin_skyline_settings: {
  "url": "https://skyline.github.com/${login}/${year}",
  "ready": "[...document.querySelectorAll('span')].map(span => span.innerText).includes('Share on Twitter')",
  "wait": 1,
  "hide": "button, footer, a"
}

          plugin_skyline_year: current-year
          plugin_stackoverflow: yes
          plugin_stackoverflow_limit: 2
          plugin_stackoverflow_lines: 4
          plugin_stackoverflow_lines_snippet: 2
          plugin_stackoverflow_sections: answers-top, questions-recent
          plugin_starlists: yes
          plugin_starlists_limit: 2
          plugin_starlists_limit_languages: 8
          plugin_starlists_limit_repositories: 2
          plugin_starlists_shuffle_repositories: yes
          plugin_stars: yes
          plugin_stars_limit: 4
          plugin_support: yes
          plugin_tweets: yes
          plugin_tweets_limit: 2
          plugin_tweets_user: .user.twitter
<div align='center'>

![Metrics](https://metrics.lecoq.io/DrDataYE?template=classic&starlists=1&lines=1&stars=1&discussions=1&projects=1&achievements=1&screenshot=1&stackoverflow=1&pagespeed=1&habits=1&languages=1&notable=1&calendar=1&introduction=1&skyline=1&support=1&tweets=1&anilist=1&music=1&posts=1&base=header%2C%20activity%2C%20community%2C%20repositories%2C%20metadata&base.indepth=false&base.hireable=false&base.skip=false&languages=false&languages.limit=8&languages.threshold=0%25&languages.other=false&languages.colors=github&languages.sections=most-used&languages.indepth=false&languages.analysis.timeout=15&languages.analysis.timeout.repositories=7.5&languages.categories=markup%2C%20programming&languages.recent.categories=markup%2C%20programming&languages.recent.load=300&languages.recent.days=14&lines=false&lines.sections=base&lines.repositories.limit=4&lines.history.limit=1&lines.delay=0&stars=false&stars.limit=4&habits=false&habits.from=200&habits.days=14&habits.facts=true&habits.charts=false&habits.charts.type=classic&habits.trim=false&habits.languages.limit=8&habits.languages.threshold=0%25&discussions=false&discussions.categories=true&discussions.categories.limit=0&starlists=false&starlists.limit=2&starlists.limit.repositories=2&starlists.languages=false&starlists.limit.languages=8&starlists.shuffle.repositories=true&calendar=false&calendar.limit=1&achievements=false&achievements.threshold=C&achievements.secrets=true&achievements.display=detailed&achievements.limit=0&notable=false&notable.from=organization&notable.repositories=false&notable.indepth=false&notable.types=commit&notable.self=false&projects=false&projects.limit=4&projects.descriptions=false&introduction=false&introduction.title=true&skyline=false&skyline.year=current-year&skyline.frames=60&skyline.quality=0.5&skyline.compatibility=false&skyline.settings=%7B%0A%20%20%22url%22%3A%20%22https%3A%2F%2Fskyline.github.com%2F%24%7Blogin%7D%2F%24%7Byear%7D%22%2C%0A%20%20%22ready%22%3A%20%22%5B...document.querySelectorAll('span')%5D.map(span%20%3D%3E%20span.innerText).includes('Share%20on%20Twitter')%22%2C%0A%20%20%22wait%22%3A%201%2C%0A%20%20%22hide%22%3A%20%22button%2C%20footer%2C%20a%22%0A%7D%0A&support=false&pagespeed=false&pagespeed.url=.user.website&pagespeed.detailed=false&pagespeed.screenshot=false&pagespeed.pwa=false&tweets=false&tweets.user=.user.twitter&tweets.attachments=false&tweets.limit=2&stackoverflow=false&stackoverflow.user=0&stackoverflow.sections=answers-top%2C%20questions-recent&stackoverflow.limit=2&stackoverflow.lines=4&stackoverflow.lines.snippet=2&anilist=false&anilist.user=.user.login&anilist.medias=anime%2C%20manga&anilist.sections=favorites&anilist.limit=2&anilist.limit.characters=22&anilist.shuffle=true&music=false&music.user=.user.login&music.limit=4&music.played.at=false&music.time.range=short&music.top.type=tracks&posts=false&posts.user=.user.login&posts.descriptions=false&posts.covers=false&posts.limit=4&screenshot=false&screenshot.title=Screenshot&screenshot.url=https%3A%2F%2Fwww.cyber1101.com&screenshot.selector=body&screenshot.mode=image&screenshot.viewport=%7B%0A%20%20%22width%22%3A%201280%2C%0A%20%20%22height%22%3A%201280%0A%7D%0A&screenshot.wait=0&screenshot.background=true&config.timezone=Africa%2FKhartoum)
<div>
</details>

<details align="center">
<summary> <b> <samp> Chess Tournament On My Profile ♟️ </samp></b></summary>
<samp>
<div align='center'>

![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=60&section=header)

# Chess Tournament On My Profile
</samp>
</details>
