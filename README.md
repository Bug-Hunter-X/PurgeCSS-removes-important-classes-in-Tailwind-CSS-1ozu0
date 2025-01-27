# PurgeCSS removes important classes in Tailwind CSS
This repository demonstrates an uncommon bug where PurgeCSS, used with Tailwind CSS, removes important utility classes from the compiled CSS, leading to unexpected styling issues.  The issue is particularly tricky to debug because it's not immediately obvious which classes are being removed.

## Setup

Clone this repository and run `npm install`. Then, run `npm run build` to compile the Tailwind CSS and build the JavaScript bundle. Observe the generated CSS file and compare it to the expected output.