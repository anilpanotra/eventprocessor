eventprocessor
==============

Event based pre and post processor
- Capable of reading events from 3rd party softwares and process them and raise new generic events
- The new events will have generic event ids and the message will be from the 3rd party event
- Event mechanism should not add recurring events and instead should count the number of instances of recuring /duplicate events
- It should be able to handle events/errors from shell/batch/OS events
