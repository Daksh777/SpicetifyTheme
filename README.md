# Installation
Run these commands:

#### Linux and MacOS:
In **Bash**:
```bash
cd "$(dirname "$(spicetify -c)")/Themes"
git clone https://github.com/Daksh777/SpicetifyTheme
spicetify config current_theme SpicetifyTheme color_scheme [dark/base]
spicetify apply
```

#### Windows
In **Powershell**:
```powershell
cd "$(spicetify -c | Split-Path)\Themes"
git clone https://github.com/Daksh777/SpicetifyTheme
spicetify config current_theme Dribbblish color_scheme [dark/base]
spicetify apply
```
