- 👋 Hi, I’m David
- 👀 I’m interested in data analysis and areas related
- 🌱 I’m currently learning C language, python and algorythims
- 📫 How to reach me: david.lanatahara@gmail.com
 uses: Platane/snk@v2
  with: github_user_name: ${{ github.davidtahara }}

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
![GitHub Snake Light](github-snake.svg#gh-light-mode-only)
![GitHub Snake dark](github-snake-dark.svg#gh-dark-mode-only)
