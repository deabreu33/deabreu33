### Hi there 👋

<!--
**deabreu33/deabreu33** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
name: Update badges

on:
  schedule:
    # Runs at 2am UTC
    - cron: "0 2 * * *"
jobs:
  update-readme:
    name: Update Readme with badges
    runs-on: ubuntu-latest
    steps:
      - name: Badges - Readme
        uses: pemtajo/badge-readme@main
        with:       
          CREDLY_USER: <username_credly> # optional, but default will use the same from github

## #30NitesOfCode:
  [Check out my progress!](https://www.codedex.io/@deabreu33587/30-nites-of-code)  
  ![@deabreu33587 #30NitesOfCode](https://www.codedex.io/api/petStatus?user=deabreu33587)
