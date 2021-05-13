
# How to Sync your Sublime Text settings on Github Gist

To do this, we need an account on Github (everything is configured directly on Github) and Sublime Text. 

1. Open Sublime Text and Install Package [Sync Settings](https://packagecontrol.io/packages/Sync%20Settings)

Steps On Github

2. **Generate new token** on Github → [Personal access tokens](https://github.com/settings/tokens/new)

3. For this (on github) → right top corner → click on Your avatar → menu → Settings → on the left side  → Developer setings → Personal access tokens - Generate new token (any name - for example - Sublime_Settings_Token) and mark only one checkbox opposite the item «gist»

4. **Create new Gist**

5. For this (on github) → right top corner → click on Your avatar → menu → Your gists → Create gist (any name - for example - My-Settings) → Create secret gist (you must insert any symbol or word in field for this)

6. When you create gist → click on gist name → open  → go address bar → click → select all symbols after your Github name (looks like - 76ee1c24762d5c33c020784f760)

7. Thats your **gist ID**

Steps in Sublime Text

8. Configure plugin Sync Settings

6. When you create gist → click on gist name → open  → go address bar → click → select all symbols after your Github name (looks like - 76ee1c24762d5c33c020784f760)

7. Open Preferences → Package Settings → Sync Settings  Settings → Default , select all or 

{
"access_token": "insert your Sublime_Settings_Token from step 3",
"gist_id": "insert your gist ID from step 6",
"auto_upgrade": true (or false)
}

and copy to the clipboard.

8. Open Preferences → Package Settings → Sync Settings → Settings → User , insert from clipboard.

9. Now save

10. Send to yours GIST Sublime Text settings - command Sync Settings: Upload 

11. Upload your Sublime Text settings to any computer with the Sync Settings plugin installed (don't forget about our  "access_token" and "gist_id") - command Sync Settings: Download


