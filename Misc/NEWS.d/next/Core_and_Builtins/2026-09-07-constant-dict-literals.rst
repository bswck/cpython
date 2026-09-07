Optimize constant dictionary literals with at least two entries by copying a
:class:`frozendict` constant instead of inserting each entry at runtime. Each
evaluation still creates a new mutable dictionary.
