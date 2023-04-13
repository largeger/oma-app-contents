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

# 📅 21.02.2023 revealjs: locating ressources relative - not absolute
When using reveal.js together with external ressources (images) in subfolders, it is strongly recommended to add these ressources with relative locations within your markdown files - absolute paths will lead to problems when using reveal-md, because reveal-md will start to look for the ressources in some probably different subfolder.
Example markdown:
````
![junit-setup1](images/junit-import1.png)
````

# 📅 09.03.2023 IntelliJ: Validating RegEx in IntelliJ
1. set the cursor to some regex in the code
2. hit Alt + Enter
3. select "Check RegExp"
4. Enjoy :-)

# 📅 13.04.2023 team: Q&A Warmup - the question chain
for a warm-up session at the start of a training day the following method was quite successfull for me:
1. set a timer for two minutes and let every student note down some questions  
2. start be naming one student and ask a question
3. after the answer, this student will name the next one to anwer and ask one of his / her questions
4. do this until everybody has had his / her turn
