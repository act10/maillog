# maillog
## Simple access to exim mail log

*no fantastic*

just

**grep email /var/log/exim/mainlog**

or

**zgrep email /var/log/exim/mainlog.0.gz**

## USAGE

**maillog email [0-10]**

## EXAMPLE

**maillog email**

search in /var/log/exim/mainlog

**maillog email 2**

search in /var/log/exim/mainlog.2.gz
