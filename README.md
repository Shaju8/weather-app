# Weather App

Simple React weather app that fetches current weather and a 5-day forecast from OpenWeatherMap.

How to run locally:

```powershell
& "$env:ProgramFiles\nodejs\npm.cmd" install
& "$env:ProgramFiles\nodejs\npm.cmd" run start
```

How to publish to GitHub (local machine needs Git installed):

1. git init
2. git add .
3. git commit -m "Initial commit"
4. Create a repo on GitHub and add remote, e.g.:
   git remote add origin https://github.com/YOUR_USERNAME/Weather.git
5. git push -u origin main

If you have the GitHub CLI installed you can instead run:

gh repo create YOUR_USERNAME/Weather --public --source=. --remote=origin --push

