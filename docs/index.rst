Welcome to OpenAPS's documentation!
==============================================

This documentation support a self-driven Do-It-Yourself (DIY) implementation of an artificial pancreas based on the OpenAPS reference design. By proceeding to use these tools or any piece within, you agree to `the copyright <https://github.com/openaps/docs/blob/master/license.txt>`_ for more information; and `the full README here <https://github.com/openaps/docs/blob/master/README.md>`_ and release any contributors from liability, and assume full responsibility for all of your actions and outcomes related to usage of these tools or ideas.

.. WARNING:: 
Note: *We do not recommend using a PDF version of this guide. The docs are updated continuously, and with a PDF, you will not get the freshest real-time edits. Be aware if you download a PDF that when you have internet connectivity, we recommend instead having the docs pulled up in an Internet browser so you can refresh. This is especially true if you are working on a setup over the course of multiple days.*

.. note:: 
   **A Note on DIY and the "Open" Part of OpenAPS**
   
   This is a set of development tools to support a self-driven DIY implementation. Any person choosing to use these tools is solely responsible for testing and implementing these tools independently or together as a system.
   
   The DIY part of OpenAPS is important. While formal training or experience as an engineer or a developer is not a prerequisite, a growth mindset is required to learn to work with the "building blocks" that will help you develop your OpenAPS instance. Remember as you consider this project that this is not a "set and forget" system; an OpenAPS implementation requires diligent and consistent testing and monitoring to ensure each piece of the system is monitoring, predicting, and controlling as desired. The performance and quality of your system lies solely with you.
   
   This community of contributors believes in "paying it forward," and individuals who are implementing these tools are asked to contribute by asking questions, helping improve documentation, and contributing in other ways. Have questions? Hop into `Gitter <https://gitter.im/nightscout/intend-to-bolus>`_ and ask anytime!


.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Before You Begin

   # docs/introduction/index
   Understanding this guide (read me first!) <docs/introduction/understand-this-guide>
   docs/introduction/contribute
   docs/introduction/communication-support-channels
   
.. toctree::
   :maxdepth: 2
   :glob:
   :caption: General Setup
   
   # docs/walkthrough/phase-0/index
   docs/walkthrough/phase-0/setup
   docs/walkthrough/phase-0/baseline-data
   docs/walkthrough/phase-0/hardware/hardware
   Compatible Pumps <docs/walkthrough/phase-0/hardware/pump>
   Compatible CGMs <docs/walkthrough/phase-0/hardware/CGM>
   docs/walkthrough/phase-0/hardware/edison
   Understanding the Explorer Board "rig" <docs/walkthrough/phase-0/understanding-your-Explorer-Board-rig>
   docs/walkthrough/phase-0/setup-edison
   FOR MAC: Edison/Explorer Board Setup <docs/walkthrough/phase-0/edison-explorer-board-Mac>
   FOR WINDOWS: Edison/Explorer Board Setup <docs/walkthrough/phase-0/windows-edison>
   Make Your First PR <docs/walkthrough/phase-0/loops-in-progress>
   
   
.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Visualizing & Monitoring
   
   # docs/walkthrough/phase-1/index
   Setting up Nightscout (recommended) <docs/walkthrough/phase-1/nightscout-setup>
   Offline Looping/Monitoring Offline <docs/walkthrough/phase-1/offline-looping-and-monitoring>
   Papertrail (optional) <docs/walkthrough/phase-1/papertrail>
   Handy shortcuts to add <docs/walkthrough/phase-1/add-alias>
   
.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Creating your DIY Closed Loop
    
   #  docs/walkthrough/phase-2/index   
   --Setup Script-- <docs/walkthrough/phase-2/oref0-setup>
   Troubleshooting setup script <docs/walkthrough/phase-2/troubleshoot-oref0-setup>
   docs/walkthrough/phase-2/accessing-your-rig
   Add other wifi on the go <docs/walkthrough/phase-2/on-the-go-wifi-adding>
   Update your rig <docs/walkthrough/phase-2/update-your-rig>
   
.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Understanding Your Loop and Tweaking Settings
   
   # docs/walkthrough/phase-3/index  
   Understand what your rig is doing & why <docs/walkthrough/phase-3/Understand-determine-basal>
   Updating preferences & more <docs/walkthrough/phase-3/beyond-low-glucose-suspend>

.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Advanced Features 
   
   # docs/walkthrough/phase-4/index  
   Usability: Tips & Tricks <docs/walkthrough/phase-4/Usability-considerations>
   Tell us you're looping! <docs/walkthrough/phase-4/keeping-up-to-date>
   Advanced Features (AMA, etc.) <docs/walkthrough/phase-4/advanced-features>
   docs/walkthrough/phase-4/bluetooth-tethering-edison
   docs/walkthrough/phase-4/ifttt-integration
   docs/walkthrough/phase-4/autotune
   docs/walkthrough/phase-4/data-commons-data-donation

.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Resources/Reference
   
   Resources <docs/Resources/index>
   reference/index

