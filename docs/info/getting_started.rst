Quick Start
###########

A more up-to-date version of this document can be found on the main repository README:
https://github.com/sccn/labstreaminglayer/blob/master/README.md

The most common way to use LSL is to use one or more applications with integrated LSL functionality.

* Take a look at the list of `supported devices <https://labstreaminglayer.readthedocs.io/en/latest/info/supported_devices.html>`_ and follow the instructions to start streaming data from your device. If your device is not in the list then see the "Getting Help" section below.
* Download `LabRecorder <https://github.com/labstreaminglayer/App-LabRecorder>`_ from its `release page <https://github.com/labstreaminglayer/App-LabRecorder/releases>`_. (Note that LabRecorder saves data to `Extensible Data Format (xdf) <https://github.com/sccn/xdf>`_ which has its own set of tools for loading data after finishing recording.)
* Use LSL from your scientific computing environment. LSL has many language interfaces, including Python and Matlab.
    * Python users need only ``pip install pylsl`` then try some of the `provided examples <https://github.com/labstreaminglayer/liblsl-Python/tree/master/pylsl/examples>`_.
    * The `Matlab interface <https://github.com/labstreaminglayer/liblsl-Matlab/>`_ is also popular but requires a little more work to get started; please see its README for more info.

If you are not sure what you are looking for then try browsing through the code which has submodule links to different repositories for tools and devices (Apps) and language interfaces (LSL). When you land in a new repository then be sure to read its README and look at its Releases page.

Getting Help
############

If you are having trouble with LSL then there are few things you can do to get help.

* `Read the docs <https://labstreaminglayer.readthedocs.io/>`_
* Search GitHub issues in the `main repository <https://github.com/sccn/labstreaminglayer>`_, in the old `archived repository <https://github.com/sccn/lsl_archived>`_, and in the submodule for your App or language interface of interest.
* Create a new GitHub issue. Please use the repository specific to the item you are having difficulty with. e.g. if you are having trouble with LabRecorder then open a new issue in its repository. If you don't know which repository is best then you can use the parent sccn/labstreaminglayer repository.
* Join the LabStreamingLayer `#users` channel on Slack. `Invite Link <https://join.slack.com/t/labstreaminglayer/shared_invite/enQtMzA2NjEwNDk0NjA5LTcyYWI4ZDk5OTY5MGI2YWYxNmViNjhkYWRhZTkwYWM0ODY0Y2M0YzdlZDRkZTg1OTUwZDU2M2UwNDgwYzUzNDg>`_. Someone there may be able to get to the bottom of your problem through conversation.
* You may also wish to subscribe to the `LSL mailing list <https://mailman.ucsd.edu/mailman/listinfo/lsl-l>`_
