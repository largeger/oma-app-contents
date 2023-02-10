# Things to learn and investigate
- [Fly.io](https://fly.io/) and moving stuff from Heroku

---
# 📅 10.02.2023 windows: ports: How to kill processes that block ports on Windows?
https://stackoverflow.com/questions/39632667/how-do-i-kill-the-process-currently-using-a-port-on-localhost-in-windows

# 📅 02.02.2023 revealjs: Using reveal-md for locally hosted presentations
I used the IDE integrated "one-click" hosting solution to present my reveal.js slide until then.
I learned: There is a tool (reveal-md)[https://github.com/webpro/reveal-md] which can be used to run the one-click solution from command line (which makes the useage independend from particular IDE features).
After installation I need the following command (run in the root-dir of my project) to start the presentation:
````
reveal-md . --separator "\n---slide---" --vertical-separator "\n---vert---" -w
````
