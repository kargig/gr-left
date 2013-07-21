gr-left
=======

A graph of the Greek Left

=======

Prerequisites:
 * graphviz

Install graphviz on Linux:

Debian/Ubuntu:  aptitude install graphviz
Gentoo:         emerge graphviz 

Fedora: http://www.graphviz.org/Download_linux_fedora.php (install repo + yum install graphviz)

Install graphviz on Windows:
click, click, click, download http://www.graphviz.org/Download_windows.php, click, click, click,
install downloaded file, click, click, click

=======

The sample image will _always_ be outdated. I don't plan to update it with every update of the dot file, so go and create your own graph.

To create a new graph use the following command:
$ dot -Tjpg gr-left.dot -o gr-left.jpg

=======

Most data was acquired through other people's articles, newspapers and wikipedia.
Data might not be very accurate, if you have better knowledge of any events (forks,joins,etc) please
edit the dot file and fix them.

