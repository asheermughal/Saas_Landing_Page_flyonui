01:
Install Tailwind CSS
Install tailwindcss and @tailwindcss/cli via npm.

"npm install tailwindcss @tailwindcss/cli"

02:
Create Src Folder and Two CreatFiles in Src Folder:

File No:1 "input.css"

File No:2 "output.css"

Import Tailwindcss in your "input.css File on your Src Folder

" @import "tailwindcss"; "


03:
Start the Tailwind CLI
Run the CLI tool to scan your source files for classes and build your CSS.

Run this Code on your Terminal,Basically this code is start the Server of Tailwind Css:

" npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch "

04:
Start using Tailwind in your HTML
Add your compiled CSS file to the <head> and start using Tailwind’s utility classes to style your content.

  <!-- <link href=".src/output.css" rel="stylesheet"> -->

