# clr-package
this is a apt package just `git clone` this repo first.

Here's how you can install the clr package from the local directory:

Navigate to the directory where you have the clr.deb package file.

Open a terminal in that directory.

Install the package using apt:

`bash`:
`sudo apt install ./clr.deb`
The ./ before the package filename is essential as it indicates to apt that the package is located in the current directory. 
Without it, apt would try to fetch the package from the internet.

Enter your password when prompted (if necessary).
The package installation process will begin, and apt will handle any dependencies and install the clr package on your system.

After installation, you can use the clr command (assuming it's the command provided by your package) in the terminal to run your package locally.
