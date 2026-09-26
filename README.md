# RoutineHub-Shortcuts
The JSON update files for my Shortcuts

Each shortcut's file has 7 keys:

- **version**: The human-readable version identifier of the latest update.
- **date**: The date the latest version was released.
- **short_notes**: The short description of the changes I made
- **long_notes**: The longer description of the changes I made
- **type**: The type of the release. Can be either `stable` or `beta`. All the files in this repository will be `stable`.
- **build**: The machine-readable version number of the latest update, which always increases by 1 with each update.
- **routinehub_id** or **url**: If the shortcut is posted on the website [RoutineHub](https://routinehub.co), that shortcut's RoutineHub id will be included under the key **routinehub_id**. You can access the shortcut's page on RoutineHub by navigating to the url `https://routinehub.co/shortcut/{routinehub_id}` 

    If the shortcut is not posted on RoutineHub, a direct iCloud link to it will be provided under the key **url**.

shortcuts that have not been updated in a while may not have the `build` and `type` keys.