# College Towns App Locker

Free apps from [College Towns](https://www.collegetowns.org), sorted into lockers by wing.

Live site: https://applocker.collegetowns.org

- **Education Wing:** Teaching Tools, Research Methods
- **Urbanism Wing:** Urbanism
- **Other Wing:** Parody

## Adding or changing an app

Everything is in `index.html`. Search for `EDIT YOUR APPS HERE` and add an entry to the `APPS` list:

```js
{ title:"My New App", category:"teaching", for:["Instructors"], url:"https://mynewapp.collegetowns.org",
  blurb:"One or two sentences about what it does." },
```

- `category`: `teaching`, `research`, `urbanism` or `parody` (this picks the locker)
- `for`: who it's made for, shown as tags
- `status:"soon"` marks a coming-soon app with no link
- `image`: a screenshot. Leave it out and the card shows a colored tile with the app's initials (`mono:"AB", color:"#2f6f9f"`).

Wings and lockers are set in the `WINGS` list just below `APPS`.

## Other files

- `CNAME`: the web address (applocker.collegetowns.org)
- `og.png`: the preview image shown when the link is shared
- `apple-touch-icon.png`: the icon for phone home screens

## Suggestions

The "Suggest an App" form opens the visitor's Gmail or email app with the suggestion filled in, addressed to the App Locker inbox.

## Visitor counter

Visits are counted privately with [GoatCounter](https://collegetowns.goatcounter.com) (sign in to see them). Pages are recorded with the site name in front, e.g. `applocker.collegetowns.org/`.

## Credits

Header type: Versa by James Lewis.
