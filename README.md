# AccessBrandywine
a flutter app to manage public/semi-public access to riverine resources.

### Idea.

A group of people have homes along the Brandywine River in Southeastern PA.  
They love giving people permission to access the river via their properties, but as of late they are getting overwhelmed with people they don’t know.
They’d like a simple web/mobile app, where someone could download, and ask for permission (perhaps sign a waiver), know where to park, etc.
So they could put signs up, saying download the web app, the land owners could see who was on their property, and have ability to manage it, etc.

### Possibles

- map integration to show where the user is, and where parking/access slots are.
- signup, with oAuth (facebook or google).
- permission ask/grant
- waiver - check with phone id
- track phoneid anonymously
- track usage within a geo boundary.

### Tech Stack

- ui flutter (for easy ios/android distribution)
- dart (flutter) for business logic
- firebase for Auth and DB tracking.
- May need open map API of some kind (leaflet?)
- Maybe map is hardwired?
