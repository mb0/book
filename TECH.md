Technologies
============

We can start by using markdown text documents and the git version control system. This allows
editing and forking on github.

We need a renderer for a paper and web version that is pretty and easy to use. The code to do that
must be open source and should be portable for common platforms.

The main idea is that Martin works on his version of this book and you can fork and edit your
version and share your thoughts and views for others to adopt.

Todo
----

We should think about our own requirements and investigate existing collaborative book projects and
the technologies they use.

 * How to manage chapters, paragraphs and sentences and their editing history.
 * How to manage translations.
 * How to manage discussion, details, embedded media, examples and links.

Conventions
-----------

We should use common conventions to keep things accessible and maintainable.

 * Primary medium is English (American?) language UTF-8 text documents
 * For now we use github flavored markdown documents using a git version control
 * We should prefer tabs for indentation where one could use multiple space characters
 * We should try to limit line length to 100 characters
 * The preferred font to render this work is Ubuntu Mono and generally the Ubuntu family of fonts
 * Scripts and Programs should use bash and go as first choice as convention.

License
-------

Copyright (c) 2023 Martin Schnabel. All rights reserved.

Program source code and documentation in this project is governed by a BSD-style license that can
found in the LICENSE file.

Background
----------

Martin has:

 * Written latex documents and can attest that it is not trivial to work with.
 * Written glue code to generate html files and render to wkhtmltopdf.
 * Some experience using gofpdf and recently discovered the pdfcpu project.
 * Heard good things about pandoc, but have no experience working with it.
 * A professional translator friend with domain knowledge.

Outlook
-------

Martin has a vague idea for a collaborative collection and curation of information as backbone of
distributed and leaderless movement to further common goals and lobby for human rights.
