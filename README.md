# Usage

To install [Gitorious](http://gitorious.org/gitorious) on an Ubuntu server:

    bash <(wget -qO - https://gist.github.com/raw/1287257/9592604b6d4a9035e0bacf194abdb9e59d9d117e/install_gitorious.sh)

The script has been tested on pristine copies of the following Ubuntu versions:

  * Ubuntu 10.04.3 LTS

Support for additional releases may be added in the future. If you find the script working for other releases, please let me know and I'll add them to the list.

After getting all prerequisites for the chef-solo run, the script will launch the node configuration file (https://gist.github.com/847256/#file-chef-gitorious-node-debian-json) in your default editor. Adjust the node settings to your environment, save the file and close the editor for the installation to continue.


# Troubleshooting

If you have any problems, please report them using the [issue tracker](https://github.com/inz/gitorious-cookbooks/issues).
