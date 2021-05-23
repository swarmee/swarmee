

[!["✨ Swarmee's Profile ✨, Home of FI-Comp 🗠, Join Us Following the Money](https://github.com/swarmee/swarmee/raw/main/swarmee-profile.gif)](http://www.swarmee.net/)

Visit our Website [🌐](https://www.swarmee.net) for details.


<!--
![❤️](https://github.com/swarmee/swarmee/raw/main/swarmee-profile.gif)

how to make this gif ?

I made my with https://codesandbox.io/s/github-profile-2ijk7
Then i recorded my screen to gif on Mac with Quicktime and https://gist.github.com/tskaggs/6394639

The type I added

typewriter
  .typeString("✨ Swarmee's Profile ✨")
  .pauseFor(1000)
  .deleteAll()
  .typeString("Home of FI-Comp 🗠")
  .pauseFor(1000)
  .deleteAll()
  .typeString("Join Us Following the Money 🪙")
  .pauseFor(1000)
  .deleteAll()
  .start();



Barafu's answer is alright. But, the resulting gif may have color conversion issue as ffmpeg complains on Incompatible pixel format 'rgb24' for codec 'gif'. Here is what I find works:

First, create PNG Palette:

ffmpeg -y -i input.webm -vf palettegen palette.png
Then, use the palette to produce gif:

ffmpeg -y -i input.webm -i palette.png -filter_complex paletteuse -r 10 output.gif
Source:



-->


<!--
**swarmee/swarmee** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
