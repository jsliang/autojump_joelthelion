## NAME

autojump - a faster way to navigate your filesystem

## SYNOPSIS
Jump to a previously visited directory that contains 'foo':

    j foo

Jump to a previously visited subdirectory of the current working directory:

    jc bar


Autojump can also be used to open a directory with `jo foo` and `jco bar`.
They behave like `j foo` and `jc bar` except that they open the directory
with a file manager.
Refer to [Additional Configuration](#additional-configuration) to configure
a file manager you prefer.

    jo foo
    jco bar

Show all database entries and their respective key weights:

    j --stat

## DESCRIPTION

autojump is a faster way to navigate your filesystem. It works by maintaining a
database of the directories you use the most from the command line. The `j
--stat` command shows you the current contents of the database. Directories must
be visited first before they can be jumped to.
