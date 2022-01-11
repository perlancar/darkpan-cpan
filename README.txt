This is a CPAN-like mirror that contains just my CPAN distributions, created
using OrePAN. I push to this repository automatically whenever I do a release.
If you happen to want to install one of my distributions, you can also clone
this repository to your local filesystem e.g.:

    % cd /some/path
    % git clone https://github.com/perlancar/darkpan-cpan.git

And then to install a module:

    % cpanm --mirror /some/path/darkpan-cpan \
        --mirror http://www.cpan.org/ \
        --mirror-only -n Some::Module

Later you can update the repository using:

    % cd /some/path/darkpan-cpan
    % git pull origin master
