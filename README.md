### Hi there 👋

**thananes** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: Happiness, Peace, Health, Money
- ⚡ Fun fact: Sports, Game Sports

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jorgeeemilio&layout=compact&theme=dark)


---
title: members

---

# Members


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for persona in site.data.personas %}
  ## {{ persona.nombre }} - {{ persona.edad }}
{% endfor %}
