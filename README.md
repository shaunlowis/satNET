# satNET
For code development in relation to the satNET model.

## **Overlying Idea**
If you imagine the space around the Earth as a bedsheet, you have satellites rolling across the bedsheet in orbit with earth. 
If you have add more satellites, the orbits of the rest change due to the new curve of the sheet. 
As a result of this change in orbit, you can figure out where the new satellites are and how much they curve the sheet by and therefore their mass. 
If you start with just a few satellites in the model, you can look at their orbits and can tell by their paths what objects must be affecting their orbits and where these objects are.
If we can only do it for a few satellites, it already would show promise, since ESA and NASA both have debris tracking satellites in orbit already that measure these things to a very high degree of accuracy.

## **Model outline**
Write a *procedurally* generating model that uses the deviations in orbits of satellites/space debris.
Deviations are calculated by expected orbit (orbit if only large nearby masses are taken into account) - observed orbit (actual orbit).
These deviations in orbits of the masses are then used to calculate the near-field masses around the observed mass, thereby generating a map of objects in near-earth orbit.

This leads to the creation of a self-generating model, requiring only a few highly detailed orbits at convenient locations. 

For all code development: Use [nbdev](https://github.com/fastai/nbdev) and jupyter notebooks and python files for utility functions.
[Here](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax) are tips on formatting github pages.

### Jupyter Notebook / Jupyter Labs

[Here](https://sqlbak.com/blog/wp-content/uploads/2020/12/Jupyter-Notebook-Markdown-Cheatsheet2.pdf) is a cheat sheet on the Markdown cells.
