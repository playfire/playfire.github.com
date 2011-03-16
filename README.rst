Checking out repositories using mr
==================================

 * Create a new directory to house the projects

 * Clone `playfire.github.com` first:

   $ git clone git@github.com:playfire/playfire.github.com.git

 * Symlink the `.mrconfig` into position:

   $ ln -s playfire.github.com/mrconfig .mrconfig

 * Add this `.mrconfig` to your `~/.mrtrust`:

   $ echo $(pwd)/.mrconfig >> ~/.mrtrust

 * Checkout the rest:

   $ mr checkout

 * Done!
