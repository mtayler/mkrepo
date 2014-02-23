mkrepo
======

Simple Bash script to create a new GitHub repo through the command line. Requires an OAuth Token in the format below placed in ~/.github/token or the location specified with the -t argument.

The token file should be in the format:
    
    token <your_OAuth_token>

To prevent other users from reading the token file, run `chmod 550 <token_file>`. This will give read and write permissions to the user and group, and no permissions to everyone else.
