Welcome to Window Manager's documentation!
===================================

**Window Manager** is a project to re-create a Windows 11 expirience inside of your browser with VueJS.

All programs and services come from the "Web Kernel" which is internally called Program Services. It is the core component of the Web "Operating System" which manages all proccesses, Services themselves including Graphical User Interface is a process running inside of Program Services. There is only one way to call Program Services which is through a existing process through the "Web Kernel API", however there is one exception to this. The first process is directly created within the "Web Kernel". This process loads the most basic essentials, which eventually loads all the services like Desktop Window Manager (Graphical User Interface), Secure System / Security Services and Logon Services.

.. note::

   This project is under active development.

.. toctree::

   kernelapi
   dwm
   logon
   secure
