eng_join: a simple english joiner
=================================

This module is pretty self-explanatory.

::
    >>> from eng_join import join

    >>> join(['blue', 'red', 'yellow'], conj='or', im_a_moron=True)
    'blue, red or yellow'
    >>> join(['blue', 'red', 'yellow'], conj='or')
    'blue, red, or yellow'
    >>> join(['blue', 'red'], conj='or')
    'blue or red'
    >>> join(['blue', 'red'], conj='and')
    'blue and red'
    >>> join(['blue'], conj='and')
    'blue'
    >>> join(['blue', 'red', 'yellow', 'green', 'yello'], conj='and')
    'blue, red, yellow, green, and yello'

