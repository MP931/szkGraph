This is a useful Python codes to simply modify the style of matplotlib for your presentation and academic papers.
Any type of suggestions, feedbacks, and upgrades are welcome.

# How to install?
Just download the `szkGraph.py` file on your computer (preferably to the dedicated folder), and import the file to your Python code.
`example.py` shows you how to import the file even from different directory.

# How to use?
Call `szkGraph.prepare()` to initialize the figure. Use the returned `fig, ax` for plotting.
After plotting and modifying your figure, export the figure with `szkGraph.finalize()`. 

## `szkGraph.prepare(xtitle=None,ytitle=None,w=None,h=None,r=0.7,font="arial",fontsize=20,)`
### Paramters
* xtitle: str, optional
* ytitle: str, optional
* w=None,  # width, float for inches, str for powerpoint page width, or str for paper width
* h=None,  # height, float for inches, this is optional
* r=0.7,  # ratio of height to width
* font="arial",
* fontsize=20,
