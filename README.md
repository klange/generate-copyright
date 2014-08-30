# generate-copyright.sh

Uses git history to generate fancy copyright headers for files.

    $ ./generate-copyright.sh generate-copyright.sh
     * Copyright (C) 2014 Kevin Lange

Another, more complex example:

    $ cd ~/Projects/toaruos
    $ generate-copyright.sh . | sort
     * Copyright (C) 2011-2014 Kevin Lange
     * Copyright (C) 2012 Markus Schober
     * Copyright (C) 2012 Tianyi Wang
     * Copyright (C) 2013 Josh Kilmer
     * Copyright (C) 2013 Patrick Lucas
     * Copyright (C) 2013 Steve Jenson
     * Copyright (C) 2013 Tyler Bindon
     * Copyright (C) 2014 Ivailo Monev
     * Copyright (C) 2014 Lioncash

