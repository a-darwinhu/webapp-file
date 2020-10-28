# webapp-file
請在 composer.json 中加入以下區段

```JSON
  {
    "repositories": [
        {
            "type": "github",
            "url": "git@github.com:a-darwinhu/webapp-file.git"
        }
    ],
    "require": {
      "ext-json": "*",
      "ext-curl": "*"
    }
  }
```
然後執行以下指令
$ composer require a-darwinhu/webapp-file

# Information 
Folder OptionFile file name rule is depend on ProfileSetting Function List with underscore
ex: LANGUAGE --> _language.json
