# multilingual Squarespace

The script allows you to make your Squarespace multilingual. The setup process is not very straightforward as this isn't a feature Squarespace supports by default.
The script is only tested with Bedford layout and it *does not* support secondary navigations. It can be modified easily to support them though using the tutorial link below.

Some knowledge of JavaScript and CSS is probably needed.

The code is an updated version from this tutorial: https://answers.squarespace.com/questions/124120/how-to-build-a-multilingual-site-in-squarespace-7.html

Demo: http://wildblueberry.fi

## Installation

1. Change your pages' url slugs to /`lang`/`pagename`, example: /en/home or /ch/home.
2. Go to Settings > Advanced > Code Injection and insert the code from `main.html` to the Footer-section.
3. Modify the code to your liking. You need to change the `languages` array (and maybe the HTML templates + CSS sheet)