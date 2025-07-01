<h1 align="center">Hi, I'm Jack! <br/><a href="https://www.linkedin.com/in/jack-milburn/">Senior IT Engineer</a>, Cybersecurity Professional, IT Consultant</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Nanobyte1991&label=Profile%20views&color=0e75b6&style=flat" alt="Nanobyte1991" />
</p>

<p align="center">
  <a href="https://github.com/Nanobyte1991?tab=followers">
    <img src="https://img.shields.io/github/followers/Nanobyte1991?label=Followers&style=social" alt="GitHub Badge">
  </a>
  <a href="https://github.com/Nanobyte1991?tab=repositories">
    <img src="https://img.shields.io/github/stars/Nanobyte1991?label=Stars&style=social" alt="GitHub Badge">
  </a>
</p>

<p align="center">
  <img src="https://media.giphy.com/media/ELham0Mveox9e/giphy.gif" alt="Interesting GIF">
</p>

## 👨‍💻 About Me

- 💼 Senior IT Engineer, Cybersecurity Professional, IT Consultant
- 🌱 Currently learning **Developing Cloud Security Strategies**

# Path to your GitHub profile README (local clone of Nanobyte1991/Nanobyte1991)
PROFILE_README = "../Nanobyte1991/README.md"  # Adjust path if needed

# Update GitHub profile README with new link
if os.path.exists(PROFILE_README):
    with open(PROFILE_README, "r", encoding="utf-8") as f:
        readme = f.read()

    # Replace section in README
    start_marker = "<!-- START_DAILY_REPORT -->"
    end_marker = "<!-- END_DAILY_REPORT -->"

    new_section = f"""{start_marker}
## 📊 Latest Cybersecurity Report

🛡️ [Read the report for {today}](https://github.com/Nanobyte1991/cyber-news-daily/blob/main/{filename})
{end_marker}"""

    if start_marker in readme and end_marker in readme:
        # Replace existing section
        start = readme.index(start_marker)
        end = readme.index(end_marker) + len(end_marker)
        updated = readme[:start] + new_section + readme[end:]
    else:
        # Append to end
        updated = readme + "\n\n" + new_section

    with open(PROFILE_README, "w", encoding="utf-8") as f:
        f.write(updated)

    print("✅ GitHub profile README updated.")


## PowerShell

- [PowerShell Azure Commands](https://github.com/Nanobyte1991/PowerShell-Azure-Commands)

## 📺 Study Guides

- [AZ-104 Study Notes](https://github.com/Nanobyte1991/AZ-104-Study-Notes)
- [AZ-900 Study Notes](https://github.com/Nanobyte1991/AZ-900-Study-Notes)
- [SC-900 Study Notes](https://github.com/Nanobyte1991/SC-900-Study-Notes)

## 🤳 Connect with me

<p align="center">
  <a href="https://www.linkedin.com/in/jack-milburn/">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn Badge">
  </a>
</p>

<p align="center">
  <img src="https://activity-graph.herokuapp.com/graph?username=Nanobyte1991&bg_color=1a1b27&color=be90f2&line=638fda&point=35aea1&area=true&hide_border=true" alt="GitHub Activity Graph">
</p>
