# Release Notes

* 2019-08-11: 0.0.7 
  * Simplified some of the casts and cleaned up code. 
  * Fixed issues related to major bug in fixed in `secc-0.0.9`
* 2019-08-11: 0.0.6 
  * Significant changes in API. Migration should be simple but see the examples for differences.
  * Implemented major serialization functionality for messages and ActorIds with serde.
  * Put in ground work for implementation of Remote actors.
  * Improved user ergonomics. 
* 2019-07-23: 0.0.5 
  * Various documentation and miscellaneous fixes.
  * Issue 11: Actors shouldn't panic if they cant schedule the actor.
  * Issue 16: Put in a means to allow an actor to monitor another actor.
  * Issue 25: Implement a means to lookup an Actor by its UUID.
  * Issue 27: Add the ability to register a local name for an actor.
  * Issue 29: Implement monitors for actors.
* 2019-07-18: 0.0.4-a
  * Maintenance release with some devops work, no features. 
* 2019-07-19: 0.0.3
  * I have added a large amount of copy edited documentation and fixed many spelling mistakes 
  * Fixed a couple of actual small bugs in the receiving of messages. 
* 2019-07-18: 0.0.2
  * Maintenance release with some devops work, no features. 
* 2019-07-18: 0.0.1
  * Initial release with basic actors, channel processing of messages and so on.
