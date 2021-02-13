# JSON data skeleton/bootstrap

- **description** `"description": "",`
  - The icon description
- **size** `"size": { "8": 0, "8@2x": 0, "16": 0, "16@2x": 0, "22": 0, "22@2x": 0, "24": 0, "24@2x": 0, "32": 0, "32@2x": 0, "48": 2, "48@2x": 3, "512": 0, "512@2x": 0, "scalable": 2 },`
  - Whether sizes are required for this icon. ( Mostly "Not Required", "Required", or only "Either/Any Required". Ex. "Required" for standard icons and 48 and scalable as "Either/Any Required" for applications.)
    - 0 : Not required
    - 1 : Required
    - 2 : Either/Any Require
    - 3 : Optional, Preferred
- **context**`"context": "",`
  - Icon context / context directory name (naming spec.)
- **application**`"application": { "name": "" },`
  - Additional information about the application this icon is used for.
  - Symlinks required for out of spec icon names used by applications or for duplicate icons with different names.
  - Icon Theme Creator Use
- **enviroment**`"enviroment": [ { "name": "", "note": "" } ]`
  - Additional enviroment note about the usage in various (desktop) enviroments or window managers. Ex. MATE
  - Icon Theme Creator Use


```
{
  "description": "",
  "size": {
    "8": 0,
    "8@2x": 0,
    "16": 0,
    "16@2x": 0,
    "22": 0,
    "22@2x": 0,
    "24": 0,
    "24@2x": 0,
    "32": 0,
    "32@2x": 0,
    "48": 2,
    "48@2x": 3,
    "512": 0,
    "512@2x": 0,
    "scalable": 2
  },
  "context": "",
  "application": {
    "name": ""
  },
  "enviroment": [
    {
      "name": "",
      "note": ""
    }
  ]
}
```
