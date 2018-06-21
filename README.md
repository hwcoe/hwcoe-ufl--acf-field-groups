HWCOE UFL ACF Field Groups
===========================


Advanced Custom Fields field groups used with the [HWCOE UFL](https://github.com/hwcoe/hwcoe-ufl) WordPress theme.

This is now a backup only. Field groups are included in the theme using [Local JSON](https://www.advancedcustomfields.com/resources/local-json/) and do not need to be imported using the Custom Fields menu.

If you've already imported the field groups into your WordPress site and wish to pull settings from the JSON files instead of your database (better for performance), follow the steps below. 

1. Back up your database and note all fields (on home page, landing pages, etc.) Existing field data is contained in the posts, so it should carry over, but back up anyway.
2. Copy the JSON files found in \hwcoe-ufl\inc\advanced-custom-fields\acf-json on your server into a backup location
3. In your dashboard, choose Custom Fields and delete all field groups. This will delete the field group settings from your database
4. It will also delete the JSON files from your server. Copy those from your backup location back into \hwcoe-ufl\inc\advanced-custom-fields\acf-json
5. Field groups should still appear when editing the relevant pages/posts/options. In the Custom Fields menu, instead of field groups you should see a "Sync available" notification. **Do not sync unless you want to make changes to the field groups.**

Resources
----------
- [Avoiding conflicts when using Local JSON](https://awesomeacf.com/how-to-avoid-conflicts-when-using-the-acf-local-json-feature/)
- [Understanding where your ACF field group settings are coming from](https://awesomeacf.com/understanding-where-your-acf-field-group-settings-are-coming-from/)
