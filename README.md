# stderred

stderr in red.

## Instalation

    if [ -f $HOME/lib/stderred.so ] && [ -f $HOME/lib64/stderred.so ]; then
      export LD_PRELOAD=$HOME/\$LIB/stderred.so
    fi

(http://comments.gmane.org/gmane.comp.lib.glibc.user/868)