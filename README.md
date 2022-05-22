# Volunteer Tracker

##### By: Marcus Ferreira

## Description

_This project allows users to add projects and volunteers to projects on the site._

## Technologies Used

* _Ruby_
* _Gems_
* _Bundler_
* _RSpec_
* _IRB_
* _Pry_
* _Sinatra_
* _Capybara_
* _Postgres_
* _SQL_

## Setup/Installation Requirements

* Clone or download this repository onto your desktop
* Navigate to top-level of directory
* In the main project directory, enter `bundle install` in the terminal to include necessary gems.
* Create a database on your device using postgres by inputting the following commands:
    `createdb volunteer_tracker`  
    `psql volunteer_tracker < database_backup.sql`  
    `createdb -T volunteer_tracker volunteer_tracker_test`
* After building the database, enter the command `rspec` into your terminal to confirm tests are all passing.
* Enter `ruby app.rb` into your terminal to run the repository with Sinatra.
* Run live server in VSCode, open your browser and nagivate to `http://localhost:4567/`


## Known Bugs

_There are no known bugs_

## License

[MIT](https://opensource.org/licenses/MIT)


Copyright (c) 2022 Marcus Ferreira