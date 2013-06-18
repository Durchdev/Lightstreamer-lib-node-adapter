## 1.1.0 (4 Jun 2013) ##

### New Features ###

Added the clearSnapshot method to the DataProvider object.
This leverages the extension in Lightstreamer Adapter Remoting Infrastructure 1.5.

Extended the "error" method of the DataResponse class, to make it similar to the Metadata Adapter case.
In order to issue an exception of type Subscription, a second argument valued "subscription" should be passed.
This changes the current behavior: with no second argument, a generic exception will now be issued.

Introduced the changelog.

### Bug Fixes ###

Removed incorrect but harmless incoming message parsing details.

Clarified the documentation comments and hidden items that were supposed to be private.

### Lightstreamer Compatibility Notes ###

Compatible with Adapter Remoting Infrastructure since 1.5
Still compatible with 1.4.3 if "clearSnapshot" is not used.



## 1.0.0 ##

### Initial version. ###

### Lightstreamer Compatibility Notes ###

Compatible with Adapter Remoting Infrastructure since 1.4.3