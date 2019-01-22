# Making Changes to the Website

1. Clone the repo to your laptop using `git clone https://github.com/surajrampure/imt-decal.github.io.git`
2. Make the changes you want in the `index.md` file 
3. After you've made your changes run `python publish.py`. If you get an error saying `pandoc: command not found` you need to install pandoc. If you're on MacOS simply run `brew install pandoc`, but if you're on Windows you can find instructions to install [here](https://pandoc.org/installing.html)
4. Open the `index.html` file locally to see if the changes you made look right
5. Run `python publish.py -c` to make the changes final and update the website