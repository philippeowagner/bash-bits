# bash-bits

## How to capture the output of a shell script to a variable in Unix?

    $ b=$(pwd)
    $ echo $b
    /home/user1

Soure: http://stackoverflow.com/a/10948354

## How to "templating" in a shell scripts

Rendering data into a template is easy.

    #! /bin/bash
    version="1.2.3"
    path="/foo/bar/baz"
    cat > /tmp/destfile <<-EOF
    here is some config for version $version which should
    also reference this path $path
    EOF

Source: http://serverfault.com/a/287690

## Quote text for URL for curl

Use the ``--data-urlencode`` switch. 

Soure: http://stackoverflow.com/a/2027690


