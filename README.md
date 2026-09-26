# RoutineHub-Shortcuts
The JSON update files for my Shortcuts

Each shortcut's file has 7 keys:

- **version**: The human-readable version number of the latest update.
- **date**: The date the latest version was released.
- **short_notes**: The short description of the changes I made
- **long_notes**: The longer description of the changes I made
- **type**: The type of the release. Can be either `stable` or `beta`. All the files in this repository will be `stable`.
- **build**: The machine-readable version number of the latest update, which always increases by 1 with each update.
- **routinehub_id** or **url**: The id of the shortcut on RoutineHub. You can access the shortcut's page on RoutineHub by navigating to the url `https://routinehub.co/shortcut/{routinehub_id}`
