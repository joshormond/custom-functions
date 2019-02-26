# custom-functions
FileMaker Custom Functions (aka user-defined functions)

'ArrayReformat' transforms any lists with any separator into a text array in any syntax you specify (JSON, CSV, etc.)

'ArrayCombine' returns a combined array from two separate arrays, similar to php's array_combine function

'CullNulls' by Debi Fuchs removes all empty items from a list. Added in effort to provide all 3rd party dependencies/includes required by our custom functions.

'GetFileSize' transform byte size into a human readable memory string (i.e. '10 Megabytes' )

'GetLayoutObjectNames' extracts list of all **named** layout objects from the specified file name and layout name and returns json, value list, or named value list.

'GetMajorVersion' extracts Major application version number (as string) from version string. This function is intended to evaluate file names, server application version,  API versions, global variables, window names, or any other string you throw at it.

'GetMinorVersion' extracts Patch and Minor application version numbers (as string) from version string. This function is intended to evaluate file names, server application version,  API versions, global variables, window names, or any other string you throw at it.

'GetRelativeDayName' returns relative day name for today, 7 days into the past, and one day into the future in abbreviated or fully spelled format.

'GetSystemPlatformVersion' transforms host OS name & version number, or OS abbreviation & browser version, to human readable format

'GetLayoutViewState' converts window view state integer values into human readable strings

'GetWindowOrientation' converts window orientation integer values ( aspect ratio and title bar position ) into human readable strings

'GetWindowStyle' converts window style integer values into human readable strings

'JSONExplode' transforms JSON into a return-delimited list similar to YAML
