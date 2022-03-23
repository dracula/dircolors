### [dircolors](https://www.gnu.org/software/coreutils/manual/html_node/dircolors-invocation.html#dircolors-invocation)

This theme requires a [terminal that supports 24-bit color ANSI escape sequences](https://en.wikipedia.org/wiki/ANSI_escape_code#24-bit).

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/dircolors.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/dircolors/archive/master.zip) option and unzip them.

#### Activating theme

The `.dircolors` file contains the theme.

Chances are that your system is already set up to load `.dircolors` from your home dir.
This is known to be the case on many popular Linux distributions such as Ubuntu, Debian, Fedora, CentOS, and many more.
If so, simply placing the file there is enough; either by copying, or symlinking from a git checkout you intend to keep around and update.
The file name may vary slightly, consult your shell startup scripts for details.

If your system does not have this functionality out of the box, see the
[dircolors documentation](https://www.gnu.org/software/coreutils/manual/html_node/dircolors-invocation.html#dircolors-invocation)
for generic instructions how to activate it. Once you get it working, you may want to include the setup in your shell startup scripts.
