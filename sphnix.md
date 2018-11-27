## Dependency
  * pip install sphnix
  * pip install rinohtype
  
## How to use
  * Create a folder called *docs* that is parallel to the *my_code_folder*
  * `cd docs`, run `sphinx-quickstart` (make sure auto-doc is selected "yes")
  * `cd source`, `vim conf.py`
    * change the path to `sys.path.insert(0, 'xxxx/my_code_folder')`
    * add `'rinoh.frontend.sphinx'` to extension
    * uncomment `latex_elements`
    * change `master_doc = 'modules'`
  * (Optional) Add addition comments in *index.rst*
  * Produce html documentation, run `make html`
  * Produce pdf documentation, run `sphinx-build -b rinoh source _build/rinoh`




## Reference

[website1](https://medium.com/@richyap13/a-simple-tutorial-on-how-to-document-your-python-project-using-sphinx-and-rinohtype-177c22a15b5b)

