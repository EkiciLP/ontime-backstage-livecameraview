# Ontime Backstage Livecameraview

This project implements a stream in an ontime backstage view.  
For this to work, you must copy the folder to Ontime's external folder and create a custom field named ‘videourl’ in the Ontime project.

### Custom Fields
- **backstage_***: any field with this prefix will be added to the notes section (always takes the next event)
- **secondaryimg**: The Image display in an alternating manner on the video area (always takes the next event)

## Third-Party Licenses

This project makes use of third-party software. All of them are listed below.

### Ontime

This project uses the API of [Ontime](https://github.com/cpvalente/ontime), a browser-based application that manages event rundowns, scheduling, and cueing.

**License:** GPL License  
Copyright (c) 2021 Carlos Valente @ light-dev

You can find the full license in the [Ontime License](https://github.com/cpvalente/ontime/blob/master/LICENSE.md).
