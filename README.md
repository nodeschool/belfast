# Nodeschool Belfast
Welcome to the NodeSchool Belfast chapter's repository. We use this
repository for our website and almost all our communication.

You can see the website here: http://nodeschool.io/belfast/


## Talk with us
We utilize [GitHub Issues](https://github.com/nodeschool/belfast/issues)
like a message board and keep almost all of our communication in the open. If
for any reason you need to contact an organizer privately you may contact us
directly.


## Creating Events
Ask and you'll get contributor access to the repo. Then follow these steps.

* Create a new branch with a name in the form `month_year` e.g. `may_2016`
* Update the details for the event
  * Date
  * Venue
  * Sponsor Logo(s)

* Create a pull request to merge your branch to `gh-pages`and go live. Before this PR is merged it should have the following labels applied:
  * "Site looks good" - person making the change should not be the one to apply this!
  * "Venue confirmed"
  * "I will mentor (1)"
  * "I will mentor (2)" - don't just apply this yourself! Have at least one other mentor confirm they will attend
  * "Food sponsored"

Only when an event has all four labels can it be merged.

## Working with this repo
Clone this repo
```
git clone git@github.com:nodeschool/belfast.git
```

create your event branch eg
```
git checkout -b june_2016
```

Install npm modules
```
npm install
```

Make your changes and run the site locally
```
npm start
```
View the site by visiting [http://localhost:8080](http://localhost:8080)