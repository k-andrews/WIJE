# West Indian Journal of Engineering Project

## Email Configuration on Server

Configured SMTP with that gmail account:
TODO: list of steps

To avoid Google (Gmail) detecting attempts to send email as suspicious activity, verify that application is a bonafide application on the accounts activity page.
TODO: list of steps

Etc.

## Changelog
 
### Commit: [8fabe](https://github.com/Snickdx/WIJE/commit/8fabe1e2d68bf1c370f89402285cf89f74d619b9)

Added project to git repo with the following changes from stock OJS:

* Added [bootstrap plugin theme](https://github.com/NateWr/bootstrap3#installation)
* Added static pages: About, Editorial Team, Submissions, Contact [etc](http://138.197.231.114/ojs/index.php/testj/management/settings/website)
* Altered [NavBar](https://github.com/Snickdx/WIJE/blob/master/plugins/themes/bootstrap3/templates/frontend/components/primaryNavMenu.tpl) to link to static pages 
```
      <li>
        <a href="http://snickdx.me/ojs/index.php/testj/advisors">
          International Advisory Committee
        </a>
      </li>
      <li>
        <a href="http://snickdx.me/ojs/index.php/testj/editorial">
          Editorial Board
        </a>
      </li>
      <li>
        <a href="http://snickdx.me/ojs/index.php/testj/staff">
          Editorial Sub Committee
        </a>
      </li>
```

(TODO: re implement using the templating engine)
* Removed the information block plugin
* Currently Working On: Creating A Custom Plugin for notification side bar.
