csv__too__json
========

Tool for csv to json conversion.

Support for python 3.6+

------------
Installation
------------

::

    pip install csv__too__json


Module can be imported to your source code::

    import csv2json

    csv2json.change(
        csv_file_path: str,
        has_header: bool = False, 
        pretty_print: bool = False
    )