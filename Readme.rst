hoc.vim
=======

Syntax file for `hoc <https://en.wikipedia.org/wiki/Hoc_(programming_language)>`__. It's the scripting language used in the `NEURON simulator <http://neuron.yale.edu/neuron/>`__.

Taken from https://github.com/jgosmann/dotvim/blob/master/syntax/hoc.vim. Feel free to update/imporve it. Pull requests welcome.


Installation
------------

Place in :code:`~/.vim/syntax` or use :code:`pathogen` and the rest - you know what to do :)

At the end of your :code:`vimrc` file, add:

.. code:: vim

    au BufRead,BufNewFile *.hoc set filetype=hoc

