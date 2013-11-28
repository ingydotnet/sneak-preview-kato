# NAME

sneak-preview - Peek into a staging container

# SYNOPSIS

Push this Stackato app like this:

    stackato push -n --tail

After a while you will be given an ssh command to run. This will drop you
inside the paused staging container.  You can poke around the (temporary)
system.

# DESCRIPTION

Ever wish you could have more insight into the Stackato staging process?

This app will pause the staging process and let you ssh in.
