# environments
Administration of Python Environments commonly used within DHI.

Use with Conda to install


# matplotlib-stylelib

These are matplotlib style that configures matplotlib figures to fit neatly into the DHI Office Report template:

Install these files in `C:\Users\<yourName>\.matplotlib\stylelib` and use `plt.style.use("DHI")` to configure your 
output figure to
- 15 cm width (column width of DHI Office Template)
- golden ratio to height
- tight layout
- label font size (axis and legend) fitting to Body Text.

Other options:
- `plt.style.use("DHI-square")` : width 15 cm x height 15 cm
- `plt.style.use("DHI-wide")` : for wide column picture format
- `plt.style.use("DHI-portrait")` : Figure fits one page exactly, including caption
- `plt.style.use("DHI-landscape")` : Figure fits one page exactly, including caption, for landscape
- `plt.style.use("DHI-portrait-A3")` :  Figure fits A3 page portrait exactly, good for appendices
- `plt.style.use("DHI-landscape-A3")` : Figure fits A3 page landscape exactly, good for appendices
