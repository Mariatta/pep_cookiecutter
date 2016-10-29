pep_cookiecutter
================

The unofficial way to start authoring your own PEP (Python Enhancement Proposal)

To official way to author your own PEP is described in PEP 1.

This is a side project for myself and I don't expect anyone using it other 
than for entertainment purpose.

Always dreamed of writing your own PEP? You can now get started quickly.

.. code-block:: bash

	$ pip install cookiecutter

After you have cookiecutter installed:

.. code-block:: bash

	$ cookiecutter https://github.com/Mariatta/pep_cookiecutter
	Cloning into 'pep_cookiecutter'...
	remote: Counting objects: 9, done.
	remote: Compressing objects: 100% (7/7), done.
	remote: Total 9 (delta 0), reused 5 (delta 0), pack-reused 0
	Unpacking objects: 100% (9/9), done.
	Checking connectivity... done.


You will be asked some questions:

.. code-block:: bash

   project_slug [best_pep_ever]: 
   pep_title [Awesome PEP Idea]: 
   pep_author [Mariatta]: 
   pep_author_email [mariatta.wijaya@gmail.com]: 
   Select pep_type:
   1 - Standards Track
   2 - Informational
   3 - Process
   Choose from 1, 2, 3 [1]: 1
   
Once you answered all questions, you will see a new directory created (e.g. `best_pep_ever`).
Under that directory, you will see a file called pep_template.rst.

Congratulations! You drafted a new PEP (unofficially) LOL

