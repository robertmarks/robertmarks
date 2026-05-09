# GitHub Readme Stats Preview

This is how the standard `github-readme-stats` style looks.

## Single stats card

![Robert's GitHub stats](https://github-readme-stats.vercel.app/api?username=robertmarks&show_icons=true&hide_border=true&theme=transparent)

## Stats + top languages (compact)

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=robertmarks&show_icons=true&hide_border=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=robertmarks&show_icons=true&hide_border=true&theme=default"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api?username=robertmarks&show_icons=true&hide_border=true" />
</picture>

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=robertmarks&layout=compact&hide_border=true&theme=dark"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=robertmarks&layout=compact&hide_border=true&theme=default"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=robertmarks&layout=compact&hide_border=true" />
</picture>

## Notes

- It is card-style and more dashboard-like than tigattack's overview SVG.
- The public endpoint is popular but can be rate-limited at times.
- For reliability, maintainers recommend self-hosting or generating static SVGs via GitHub Actions.
