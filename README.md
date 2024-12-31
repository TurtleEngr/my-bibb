```{=html}
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html;charset=UTF-8"/>
<title>my-bib Files</title>
<link rel="stylesheet"
      href="bib.css" />
</head>
<body>
```
my-bib Files
============

My personal bibliography
------------------------

-   \<a href=\"biblio.html\"\>biblio.html\</a\> - references to: books,
    articles, websites, videos, DVDs, etc. (This is generated from:
    biblio.txt)

-   \<a href=\"biblio-note.html\"\>biblio-note.html\</a\> - Annotations
    related to Ids in biblio.txt (This is generated from
    biblio-note.org)

How biblio is built and used
----------------------------

-   Source: <https://github.com/TurtleEngr/my-bib>
    -   biblio.txt - master file for biblio.html and for DB import.
    -   biblio-note.org - extra notes for biblio items.
    -   doc.odt - link to a LibreOffice document that will be updated
        from the DB.
    -   etc/ - config file for the \"bib\" command.
    -   status/ - datestamp of when bib commands are run.
    -   Makefile - build processes.
-   [libre-bib](https://github.com/TurtleEngr/libre-bib) - this tool
    imports the biblio.txt into a DB. The DB is then used by libre-bib
    and a Libreoffice document to generate the document\\\'s
    Bibliography.
