Two additions might be good:

1. Introduce an option to define other mandatory fields (or none)

2. Introduce an option to force ocrmypdf on a PDF, although it contains text

Current tests run in a virtualenv:

    $ virtualenv --python python3 venv
    $ ./venv/bin/python setup.py
    $ ./venv/bin/invoice2data \
        --exclude-build-in-templates --template-dir tpl output.pdf
