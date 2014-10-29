# bash-bits

## "Templating" in shell scripts

    #! /bin/bash
    version="1.2.3"
    path="/foo/bar/baz"
    cat > /tmp/destfile <<-EOF
    here is some config for version $version which should
    also reference this path $path
    EOF

Source: 

## Quote text for URL for curl

Use the ``--data-urlencode`` switch. 

Soure: http://stackoverflow.com/a/2027690


