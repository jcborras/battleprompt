battleprompt
============

**Moved to the configuration files repo**

Customize the snippet below for your environment and add it somewhere
in `~/.bashrc`:

    battlepromptdir=$HOME/src/git-trees/battleprompt
    if [ -f $battlepromptdir/promptrc ] ; then
      source ~/src/git-trees/battleprompt/promptrc 
    fi
    unset battlepromptdir



