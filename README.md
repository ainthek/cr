# cr (Code Reviews)

This is random notes (blog) of findings and code review topics.
Just notes, later links with explanations, one day maybe a reasonable document.

## 22.5.2019 node.js, dependencies vs. devDependencies

- TLDR: Do not put mocha into dependencies. Put is into devDependencies

- Example: <https://github.com/IonicaBizau/remove-blank-lines/issues/11>

- Detection: using my own '../npma' project, at Dec. 2018, 4357 npm packages had mocha as dependency and 2125205 as devDependency
