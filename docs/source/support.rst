.. _support:

Support
=======

You can email help requests to elastic-blast-support@ncbi.nlm.nih.gov

Please help the development team help you: 

* When reporting problems, please provide us with:

   * Your configuration file
   * The ElasticBLAST logfile (``elastic-blast.log`` by default)
   * Your system's information, i.e. the output of the commands below:

.. code-block:: bash

    uname -a
    python3 -m sysconfig
    env
    gcloud info


* Always use the ``--loglevel DEBUG`` option (for now).
* Consider using the unix ``screen`` (`wikipedia <https://en.wikipedia.org/wiki/Script_(Unix)>`_, `man page <https://man7.org/linux/man-pages/man1/script.1.html>`_) tool to capture the
  output of your usage of ElasticBLAST and attaching the session log to your
  problem report. 

Thanks! :)

Please see also the list of :ref:`known issues<issues>`.
