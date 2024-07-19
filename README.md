![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

To run a backend Python file, type `python3 app.py` if your Python file is named `app.py`, of course.

By Default, Gitpod gives you superuser security privileges. Therefore, you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you, so do not share it. If you accidentally make it public, you can create a new one with _Regenerate API Key_.

### Connecting your Mongo database

- **Connect to Mongo CLI on a IDE**
- navigate to your MongoDB Clusters Sandbox
- click **"Connect"** button
- select **"Connect with the MongoDB shell"**
- select **"I have the mongo shell installed"**
- choose **mongosh (2.0 or later)** for : **"Select your mongo shell version"**
- choose option: **"Run your connection string in your command line"**
- in the terminal, paste the copied code `mongo "mongodb+srv://<CLUSTER-NAME>.mongodb.net/<DBname>" --apiVersion 1 --username <USERNAME>`
  - replace all `<angle-bracket>` keys with your own data
- enter password _(will not echo **\*\*\*\*** on screen)_

------

# User story 1

* _In order_ to provide my opinion with regards to a certain running topic or event as a user I can select and submit an answer from the poll

## Acceptance Criteria user story 1

* The form for voting on polls should be available and visible
* The poll should be in an appropriate area for the user
* The poll should allow my option to be selcted and submitted

## Tasks

* [x] Design/style form format for new polls
* [ ] Create form for polls template
* [ ] Implement polls into website area for voting by the user
* [ ] Create submission functionality and user response on success

# User story 2

* _In order_ to provide anonymous feedback as a user, I can choose to hide my identity in the poll response.

## Acceptance Criteria user story 2

* The option should be provided as a checkbox.
* The checkbox should be "checked" by default.
* The option should appear next to the submit button.

## Tasks

* [ ] Make a checkbox for anonymous feedback
* [ ] Make checkbox "checked" as the default
* [ ] Update the view (html and css) to include the checkbox and to show the name of the submitter
* [ ] Update the controller function
* [ ] Update test scripts
* [ ] Test functionality
