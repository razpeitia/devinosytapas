:tocdepth: 1

.. |grappelli| replace:: Grappelli
.. |filebrowser| replace:: FileBrowser

.. _faq:

FAQ
===

Some questions, some answers.

Why should I use the |filebrowser|?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If you need your editors or customer to manage files, the |filebrowser| is an alternative to an FTP-client. Moreover, with the |filebrowser| you are able to define different image-versions according to your websites grid.
Alternatives to the |filebrowser| can be found at http://djangopackages.com/grids/g/file-managers/.

I want to use |filebrowser|, but I don't want to use |grappelli|?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

|grappelli| is a requirement for using the |filebrowser|. There are several filebrowser-no-grappelli versions (most of them on GitHub), but we don't follow the development.

I need help!
^^^^^^^^^^^^

see :ref:`Troubleshooting <troubleshooting>`.

Why are there no fancy effects?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The |filebrowser| is about managing files. We think that you should prepare your files *before* uploading them to the server.

How do I upload to another server?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Use a custom storage engine, see https://docs.djangoproject.com/en/1.3/howto/custom-file-storage/.

Why should I need image-versions?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You need image-versions if your website is based on a *grid*.

Is the |filebrowser| stable?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We've developed the |filebrowser| for a couple of years and use it with almost all of our clients. That said, |grappelli| is the more stable and mature application.

How can I contribute?
^^^^^^^^^^^^^^^^^^^^^

Help is very much needed and appreciated. Test the |filebrowser| and submit feedback/patches.

Who develops the |filebrowser|?
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The |filebrowser| is developed and maintained by Patrick Kranzlmüller & Axel Swoboda of `vonautomatisch <http://www.vonautomatisch.at>`_.