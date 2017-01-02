# MovieTime

## Goal

To be able to tell Google Home I want to watch a movie and have that trigger a number of events.

* "Hey Google, I want to watch `movie name here`

Google Assistant (via IFTTT?) triggers a search of the following streaming services:

* Netflix
* Amazon Prime
* HBO Now
* Plex (local)

### If successful

Reply with "You can watch `movie name` on `service name`. Would you like to watch that now?
* "Yes!"
* Trigger Harmony Hub to turn TV on (or change input), go to `streaming service` and play `movie name`

### If unsuccesful

Reply with "`movie name` is not on any of your services. Would you like to download it?"
* "Yes!"
* Trigger an add to queue in CouchPotato
* When succesfully downloaded, moved & added to Plex reply with "`movie name` is available now in Plex. Would you like to watch it?"
* Trigger above success method
