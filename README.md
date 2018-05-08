# MeasureCamp Session Board
A digital timetable for unconferences inspired by the boards used at [MeasureCamp](http://measurecamp.org/).

## Running
First install dependencies:

`npm install`

Then run the webserver:

`node ./web.js`

And the board should then be available at [port 5000](http://localhost:5000/)

## Configuration
Most data is stored in a [Google Sheet](https://docs.google.com/spreadsheets/d/19NhwtckaO9KfabuFPX9vlcNEnjOUXVy1OAq9kJgA5Rk/preview) for editing.
The rest is hardcoded for [MeasureCamp Columbus 2018](http://columbus.measurecamp.org/).

## TODOs, desired features:
### Talks
- [x] Add talk title
- [x] Add talk description
- [x] Add talk technical difficulty
- [ ] Add talk audience
- [x] Add talk start/end
- [x] Add talk metadata
- [ ] Add talk slides
### Venue
- [ ] Clickable maps
- [x] Add/edit rooms
- [x] Add room capacity
### Sponsor
- [x] Add sponsor title
- [ ] Add sponsor website
- [ ] Add sponsor image
- [ ] Add sponsor profiles
### Speakers
- [x] Add speaker name
- [ ] Add speaker profile
- [x] Add speaker social links
### Schedule
- [ ] Add/edit talks in schedule
- [ ] Add fixed duration breaks
- [ ] Add variable duration breaks
- [ ] Add personalized schedule
- [ ] Push notifications for schedule changes
- [ ] Add afterparty information
- [ ] Up next' visualisation
### Data Entry
- [x] Allow manual data entry
- [ ] Allow automatic data entry
### Other
- [ ] Afterparty information
- [ ] Safety information
