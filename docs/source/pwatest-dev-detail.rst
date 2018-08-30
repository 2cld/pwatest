pwatesttest dev detail
======================

Step - pwatest-checkpoint-01_
--------------------------------

Just getting things setup for baseline pwatest ReactJS project with documentation on 2cld-pwatest-readthedocs_

#. Create new React-App Web Application::

    catmini:2cld cat$ npx create-react-app pwatest

#. Pull in docs structure::

    macci:pwatest cat$ cd ~/2cld/pwatest
    macci:pwatest cat$ (copy in base docs from 2cld-readthedocs-demo_ setup)
    macci:pwatest cat$ vi docs/conf.py
    macci:pwatest cat$ vi docs/index.rst (and various others)
    macci:pwatest cat$ cd docs
    macci:docs cat$ make html (fix errors)
    macci:docs cat$ open build/html/index.html

#. Verify docs build here 2cld-pwatest-localdocs_ on local system

#. Adjust .gitignore (add docs/build/)::

    # See https://help.github.com/ignore-files/ for more about ignoring files.
    
    # dependencies
    /node_modules

    # testing
    /coverage

    # production
    /build

    # misc
    .DS_Store
    .env.local
    .env.development.local
    .env.test.local
    .env.production.local

    npm-debug.log*
    yarn-debug.log*
    yarn-error.log*

    #######################
    # readthedocs gitignore

    # sphinx build folder
    docs/build/



Step Template
=============

Step-NN - pwatest-checkpoint-NN_
-----------------------------------

The NAME_OF_GOAL Step-NN intent is to blahblahblah.

#. Create NAME_OF_GOAL for pwatest-checkpoint-NN_

    #. tbd  
    #. tbd 

#. Produce pwatest-checkpoint-NN_ NAME_OF_GOAL

    macci:pwatest cat$ cd ~/2cld/pwatest/docs
    macci:docs cat$ vi source/pwatest-dev-detail.rst (update doc)
    macci:docs cat$ make html 
    macci:docs cat$ open build/html/index.html (verify docs)
    macci:pwatest cat$ cd ~/2cld/pwatest
    macci:pwatest cat$ git add *
    macci:pwatest cat$ git commit -m "commit for pwatest-checkpoint-NN - NAME_OF_GOAL"
    macci:pwatest cat$ git tag pwatest-checkpoint-NN
    macci:pwatest cat$ git push
    macci:pwatest cat$ git push origin pwatest-checkpoint-NN
    
#. Verify checkpoint pwatest-checkpoint-NN_

Resources
---------

#. Github Project Repo: 2cld-pwatest-github_
#. Read the Docs: 2cld-pwatest-readthedocs_
#. ReadTheDocs demo files: 2cld-readthedocs-demo_


.. _readthedocs: https://readthedocs.org/
.. _2cld-readthedocs-demo: https://github.com/2cld/readthedocsdemo
.. _2cld-pwatest-readthedocs: http://2cld-pwatest.readthedocs.io/en/latest/
.. _2cld-pwatest-localdocs: http://~/2cld/pwatest/docs/build/html/index.html
.. _2cld-pwatest-github: https://github.com/2cld/pwatest


.. _firebase-console: https://console.firebase.google.com/

.. _pwatest-checkpoint-NN: https://github.com/2cld/pwatest
.. _pwatest-checkpoint-01: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-01
.. _pwatest-checkpoint-02: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-02
.. _pwatest-checkpoint-03: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-03
.. _pwatest-checkpoint-04: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-04
.. _pwatest-checkpoint-05: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-05
.. _pwatest-checkpoint-06: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-06
.. _pwatest-checkpoint-07: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-07
.. _pwatest-checkpoint-08: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-08
.. _pwatest-checkpoint-09: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-09
.. _pwatest-checkpoint-10: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-10
.. _pwatest-checkpoint-11: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-11
.. _pwatest-checkpoint-12: https://github.com/2cld/pwatest/tree/pwatest-checkpoint-12

.. _youtube-FlutterWireUpFirebaseAuthiOS: https://www.youtube.com/watch?v=3nFIMej3Tvw
.. _youtube-ios-tutorial-testflight-1: https://www.youtube.com/watch?v=1CcCKQHjDpw
.. _youtube-ios-tutorial-testflight-2: https://www.youtube.com/watch?v=1DVLaMmGxR8

.. _github-projects-configure-projects: https://help.github.com/articles/configuring-automation-for-project-boards/
