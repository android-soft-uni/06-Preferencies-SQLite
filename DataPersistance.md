# 

## Temp solution / Memory

#### onSaveInstanceState

| Persistance Option | Type of data saved | Length of time saved |
|--------------------|:-------------------|:---------------------|
| onSavedInstanceState| key / value (complex values) | While app is open | 

## File system

#### SharedPreferences

| Persistance Option | Type of data saved | Length of time saved |
|--------------------|:-------------------|:---------------------|
| onSavedInstanceState| key / value (complex values) | While app is open | 
| SharedPreferences | key / value (primitive values) | Between app and phone restarts |

#### SQLite Database

| Persistance Option | Type of data saved | Length of time saved |
|--------------------|:-------------------|:---------------------|
| onSavedInstanceState| key / value (complex values) | While app is open | 
| SharedPreferences | key / value (primitive values) | Between app and phone restarts |
| SQLite Database | Organized, more complicated text / numeric / boolean data | Between app and phone restarts |

#### Internal / External storage

| Persistance Option | Type of data saved | Length of time saved |
|--------------------|:-------------------|:---------------------|
| onSavedInstanceState| key / value (complex values) | While app is open | 
| SharedPreferences | key / value (primitive values) | Between app and phone restarts |
| SQLite Database | Organized, more complicated text / numeric / boolean data | Between app and phone restarts |
| Internal / External storage | Multimedia or large data | Between app and phone restarts | 

## Services

#### Server (e.x Firebase)

| Persistance Option | Type of data saved | Length of time saved |
|--------------------|:-------------------|:---------------------|
| onSavedInstanceState| key / value (complex values) | While app is open | 
| SharedPreferences | key / value (primitive values) | Between app and phone restarts |
| SQLite Database | Organized, more complicated text / numeric / boolean data | Between app and phone restarts |
| Internal / External storage | Multimedia or large data | Between app and phone restarts | 
| Server (e.x Firebase) | Data than multiple phone will access | Between app and phone restarts, deleting the app, using a different phone, etc. |
