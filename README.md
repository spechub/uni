# uni
    for d in util events posixutil reactor htk graphs uDrawGraph; do cp LICENSE $d; done
    
In every directory do:

    cabal v1-configure; cabal v1-build; cabal v1-install; cabal check; cabal sdist;
