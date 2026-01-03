# AP-42: Compilation of Air Emissions Factors from Stationary Sources 
<!-- https://www.epa.gov/air-emissions-factors-and-quantification/ap-42-compilation-air-emissions-factors-stationary-sources#5thed -->

## Appendix A. Miscellaneous Data and Conversion Factors
<!-- https://www.epa.gov/sites/default/files/2020-11/documents/appa.pdf -->

### Tips

Quick setup — if you’ve done this kind of thing before
or https ssh `git@github.com:tthen/conver.git`

Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore. 
or create a new repository on the command line

```
echo "# conver" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:tthen/conver.git
git push -u origin main
```
or push an existing repository from the command line

```
git remote add origin git@github.com:tthen/conver.git
git branch -M main
git push -u origin main
```


### Python Docstrings Tutorial : Examples & Format for Pydoc, Numpy, Sphinx Doc Strings
<!-- https://www.freecodecamp.org/news/learn-software-design-basics/ -->

Python documentation string, commonly known as docstring, is a string literal, and it is used in the class, module, function, or method definition. Docstrings are accessible from the doc attribute (__doc__) for any of the Python objects and also with the built-in help() function. An object's docstring is defined by including a string constant as the first statement in the object's definition.

The general format for writing a Multi-line Docstring is as follows:

```python
def some_function(argument1):
    """Summary or Description of the Function

    Parameters:
    argument1 (int): Description of arg1

    Returns:
    int:Returning value

   """

    return argument1

print(some_function.__doc__)
```

