Meteor Community Chat
=====================

Abuse GitHub and use it as a chat with GitHub users who don't display an email, or just prefer GitHub.

Great for contacting publishers of [Atmosphere](http://atmospherejs.com) packages that no longer have a repo, but the GitHub account still exists. If you are such a user it's probably because you've published a wrapper package, have [worked with the original authors to publish official Meteor packaging](https://github.com/MeteorCommunity/discussions/issues/14), and are now asking you to hide your package from Atmosphere searches (while still keeping it installable by dependencies). You can do so with:

    meteor admin set-unmigrated package:name
    
To remove `mrt` as a contributor:

    meteor admin maintainers <your_username>:<your_package> --remove mrt

If you were originally the maintainer on the old package system, you can attach your Meteor Developer account at http://atmosphere.meteor.com/accounts, then ping @tmeasday to give you ownership of the old package.
