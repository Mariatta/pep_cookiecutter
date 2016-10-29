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
	Cloning into 'HelloCookieCutter1'...
	remote: Counting objects: 37, done.
	Unpacking objects:  21% (8/37)
	remote: Total 37 (delta 19), reused 21 (delta 3), pack-reused 0
	Unpacking objects: 100% (37/37), done.
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

Congratulations! You unofficially drafted a new P

