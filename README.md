Steps to work on this project.

1. Clone this repository.
2. Make sure node in installed on your computer. And run npm install at root of project.
3. Run **npx tailwindcss -i ./src/tailwind.css -o ./docs/styles.css --watch** (This command is to run tailwind compiler everytime changes are made so that classes of tailwind can work.)
4. Make changes to files in docs folder only. Put everything inside docs folder, because we have deployed files inside that folder only.
5. Again after making changes run these git commands to deploy new changes - 
- git add .
- git commit -m "Commit message"
- git push

Deploy process (if not done yet and homepage is not live) -

Go to repository settings then Pages and then choose branch main and change folder from /(root) to /docs then click save.


Colors used.

Logo Green 1 - #03DE74

Logo Green 2 - #83FFC0

Logo Blue - #58FFE6

Text Green 3 - #55FFCC

Background Blue - #0B1F52

