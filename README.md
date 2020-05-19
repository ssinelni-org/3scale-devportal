# 3scale-devportal

3Scale Dev Portal simple customization example for internal API Developer Portal scenario.

Features:
- Homepage (signed out): removed all references to Echo API - Just sign up and/or sign in
- Homepage (signed in): removed all references to Echo API - Just see all your credentials
- Documentation (signed in): Displays list of all available APIs, allows to click on each to show corresponding ActiveDocs
- Main layout: All pages branded with {{ provider.name }} Liquid Drop

How to use:
- Simply replace the full contents of each page with that provided inside the files in this repo. Keep a backup of your original file's content!
