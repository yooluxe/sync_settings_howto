
<img src="docs/spacer.png" width="1" height="1">

## How to Sync your Sublime Text settings on Github Gist.

You need an account on Github (everything is configured directly on Github) and Sublime Text 

<img src="docs/spacer.png" width="1" height="1">

<img src="docs/view.png">

<img src="docs/spacer.png" width="1" height="1">

1. Open Sublime Text and Install Package [Sync Settings](https://packagecontrol.io/packages/Sync%20Settings)

```
Steps On Github
```

#### **Generate new token** on Github → [Personal access tokens](https://github.com/settings/tokens/new)

2. Click Your avatar menu → Settings → Developer setings → Personal access tokens - Generate new token with any label (for example - Settings_Token) and mark only one checkbox - «gist»

##### **Create new Gist**

3. Click Your avatar menu → Your gists → Create Gist with any label (for example - ST_Settings) → Create secret gist (you must insert any symbol in field)

#### Take your **gist ID**

4. Click on Gist label → go address bar → select all symbols (your gist ID) after your Github login (looks like - 76ee1c24762d5c33c020784f760)

```
Steps in Sublime Text
```

#### **Configure plugin Sync Settings**

5. Open Preferences → Package Settings → Sync Settings → Settings → Default , select all and copy to the clipboard

6. Open Preferences → Package Settings → Sync Settings → Settings → User , insert from clipboard

7. Fill "access_token" and "gist_id" in User Sync Settings
```
{
  "access_token": "insert your Token from step 2",
  "gist_id": "insert your gist ID from step 4",
  "auto_upgrade": true (or false)
}
```
8. Now save. Thats All :+1:

<img src="../main/docs/spacer.png" width="1" height="1">

## How to Use Sync Settings plugin.

1. Send to yours GIST Sublime Text settings → command → Sync Settings: Upload

2. Upload your Sublime Text settings to any computer with the Sync Settings plugin installed (don't forget about yours "access_token" and "gist_id") → command → Sync Settings: Download
