<<<<<<< HEAD
Telescope is an open-source, real-time social news site built with [Meteor](http://meteor.com)

**Note:** Telescope is beta software. Most of it should work but it's still a little unpolished and you'll probably find some bugs. Use at your own risk :)

# Learn More
- [Telescope Site](http://telesc.pe)
- [Telescope Demo](http://demo.telesc.pe)

# License
- Telescope is distributed under the [MIT License](http://opensource.org/licenses/MIT)

# Features
- Real-time (of course!)
- Password-based and/or Twitter auth
- Notifications
- Mobile-ready & responsive
- Invite-only access for reading and/or posting
- Markdown support
- Day by day view

# Installation
- Install Meteor
- Install [Meteorite](https://github.com/oortcloud/meteorite/)
- Download or clone Telescope into /some/path
- cd /some/path
- Run `mrt`

# Running Telescope on Heroku
- Use the [Heroku buildpack for Meteorite](https://github.com/oortcloud/heroku-buildpack-meteorite) to push to Heroku: `heroku create --stack cedar --buildpack https://github.com/oortcloud/heroku-buildpack-meteorite.git`
- Add MongoHQ addon

# First Run
- Set the root URL variable used for Twitter auth (on Heroku: `heroku config:add ROOT_URL=http://your_url`)
- Fill in your Twitter keys
- The first user account created will automatically be made admin
- Check out the settings page and fill out basic things like the site's name

# Local Variables
Meteor uses local environment variables for a few things, such as configuring email. While this is straightforward to do on Heroku (see above), on a local dev environment the best way is to set up an alias for the `mrt` command. 

For example, to configure Meteor to use Mailgun for email, in your `.bash_profile` file just add:
`alias m='MAIL_URL=smtp://username:password@smtp.mailgun.org:587/ mrt'`


This can also be useful for starting Meteor on a specific port:
`alias m4='MAIL_URL=smtp://username:password@smtp.mailgun.org:587/ mrt --port 4000'`
=======
Telescope
=========

Fork of Telescope Meteor Demo.
>>>>>>> d9294a03672d60aeb3565537b861d9e139d500b5
