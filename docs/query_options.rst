==========
Query Options
==========

With SharePlum plus you can specify a QueryOptions parameter while querying GetListItems method.


RootFolder
=====

RootFolder permit to specify the subfolder containing the list data.
Without specifying it, some list would return a list of current folders.

The Where Element is probably the most commonly used. ::

    query_options = {
        "RootFolder": "PATH/TO/DIRECTORY"
    }
