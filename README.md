## Synopsis

This project is designed to provide documentation, articles and reference material with VBA solutions by and for the community.

## Contact Us

To request a new feature or report a bug, please go to: 
For live discussions, come visit us on freenode.net at ##vba, the IRC Channel.

## Contributors

For documentation on the *.rst format: http://sphinx-doc.org/latest/rest.html
For documentation on the *.md format: https://daringfireball.net/projects/markdown/syntax

For a more indepth look at setting up sphinx: http://ardalis.com/contributing-to-asp-net-5-documentation

## Installation

>1. Install your text editor.  Visual Studio 2015 is supported, but is not required.
>2. Download and install Python v3.5 or later at http://www.python.org/downloads
>3. To update the path in Windows:
>    a. Open system properties->Advanced Settings->Environment Variables->System Variables->Path
>    b. Add the python install path to the end of the variable.
>    c. Add the python install path\scripts to the end of the variable.
>4. Open the command prompt
>5. Run: pip install sphinx
>6. Run: pip install -U sphinx_rtd_theme
>7. Clone OnVBA at: https://github.com/rolenun/OnVBA
>8. CD to the clone/docs directory
>9. Run: make html
>10. If you would prefer to use Visual Studio to build the docs, goto Tools->External Tools
>    a. Click Add
>    b. Title: OnVBA
>    c. Command: $(SolutionDir)\docs\make.bat
>    d. Arguments: html
>    e. Initial Directory: $(SolutionDir)\docs\
>    f. Click the Use Output Window box
>    g. Right Click the menu bar
>    h. Click Customize->Commands->Add Command->Tools-External Command 3 (or your corresponding external command) 
>    i. This process will add a menu button that will build the site and output the information in the Output Window.

## License

This project and all contributions, including source code, articles, etc are under the MIT license.