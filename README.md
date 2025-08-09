# Hi! I'm ISU a student from Mexico


## 🚀 About Me
I'm a Systems Engineering student in Mexico.

My favorite hobby is learning new codes and practicing them.

I like trying to create my own projects or in groups.

I enjoy web development and databases.

Spanish is my native language, I like to practice English a lot.

<!---
Isu-682/Isu-682 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<img src="https://github-readme-stats.vercel.app/api?username=Isu-682&theme=radical&show_icons=true&hide_border=true&count_private=true" alt="Isu-682's GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Isu-682&theme=radical&show_icons=true&hide_border=true&layout=compact" alt="Isu-682's GitHub Stats" />

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
