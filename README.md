bin-tools
=========

Some binary tools to help me in my dev environment.

You have to clone the repository in your root user, and copy this in your .profile :

    # Includes Nans Pellicari bin tools
    if [ -d "$HOME/bin-tools" ] ; then
        PATH="$HOME/bin-tools:$PATH"
    fi
