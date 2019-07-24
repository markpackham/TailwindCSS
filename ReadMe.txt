The public end of the site is in the "dist" folder

Run this to compile css, it uses "style.css" in root and compiles material into "dist/style.css"
npm run build:css


What makes Tailwind CSS intresting is you can just apply the styling very
granularly in the html however you can if you really want makes style specific
classes in the root "style.css" file.

You can also make specific styling in the .config.js file. 
"tailwind.config.js"
In both cases be sure to run the build script after doing your work.

Tailwind CSS gives you greater control over how you make things look so there's 
less of a default samey feel that you get with something like Bootstrap