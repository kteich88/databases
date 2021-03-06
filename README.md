# OoT (Ocarina of Time) Database

The program entitled 'sql_search_engine.rb' is a postgresql database program for the hero of time based on the Nintendo series game "The Legend of Zelda: Ocarina of Time." 

While the functionality of this application is still in the works, the idea behind this assignment was to allow users to create a database from within the main application file ('sql_search_engine.rb') and pass through options utilizing option parser to seed data into the database.  

The ultimate goal behind this assignment and similar repositories that followed (zelda_database, zelda_api) is to create the ultimate Zelda API! If you are interested in contributing to this project and further collaboration towards the complete development of a Zelda API, please contact me, fork this repository and/or make a pull request. 


## Getting Started

The instructions below will help you retrieve a copy of the project to run on your local machine through the Terminal application. Please see deployment for notes on how to deploy the project on a live system.  The instructions provided are for macbook users only.

### Prerequisites

You may need to install or update the following software.

Find Terminal - to run program
  1. Open Finder. Finder is available in the Dock.
  2. Select Applications from the side bar menu.  Then unfold the Utilities folder.
  3. Double click on Terminal to initialize.

Install Homebrew - to store program files properly
  1. Open up Terminal.
  2. Run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  3. Run `brew doctor`

Install rbenv & ruby-build - to install and compile different versions of Ruby code language
  1. Open up Terminal
  2. Run `brew install ruby-build rbenv`
  3. Run `echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile`

Install ruby 2.3.1 - or latest version of Ruby
  1. Close and reopen Terminal. `rbenv install 2.3.1`
  2. After quite some time, run: `rbenv global 2.3.1`
  
Download postgresql
  1. Go to http://postgresapp.com/
  2. Move the app to the /Applications file folder.
  3. Double Click on app to run the program.

Install postgresql using brew
```
brew install postgresql
```

Once you have completed the above installation processes your system is ready to launch the program!

### Deployment

Please complete the following procedure to run the program on a live system:
  1. Open Terminal.
  2. Change your directory to the one that which you would like to save this project. `$ cd folder_name`
  3. Then run the commands `$ git clone https://github.com/kteich88/Oot_database.git` and `$ cd Oot_database`
  4. Run `$ bundle install` to install the gems necessary for this project (specified in Gemfile).
  5. Open up the app Postgres.
  6. Finally run the application `$ ruby sql_search_engine.rb -[Options] to begin seeding your database using option parser. 

## Built With

* Atom

* Postgresql

## Authors

* **Kristine Teichmann**

## Acknowledgments

* The Iron Yard - Durham

* Shigeru Miyamoto, Nintendo, The Legend of Zelda Series
