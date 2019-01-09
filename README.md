# custom-functions
FileMaker Custom Functions

'ArrayReformat' function transforms any lists with any separator into a text array in any syntax you specify (JSON, CSV, etc.)

'ArrayCombine' function returns a combined array from two separate arrays, similar to php's array_combine function

'CullNulls'function by Debi Fuchs removes all empty items from a list. Added in effort to provide all 3rd party dependencies/includes required by our custom functions.

'GetFileSize' function transform byte size into a human readable memory string (i.e. '10 Megabytes' )

'GetLayoutObjectNames' function extracts list of all **named** layout objects from the specified file name and layout name and returns json, value list, or named value list.

'GetMajorVersion' function extracts Major application version number (as string) from version string. This function is intended to evaluate file names, server application version,  API versions, global variables, window names, or any other string you throw at it.

'GetMinorVersion' function extracts Patch and Minor application version numbers (as string) from version string. This function is intended to evaluate file names, server application version,  API versions, global variables, window names, or any other string you throw at it.

'GetSystemPlatformVersion' function transforms host OS name & version number, or OS abbreviation & browser version, to human readable format

'GetLayoutViewState' function converts window view state integer values into human readable strings

'GetWindowOrientation' function converts window orientation integer values ( aspect ratio and title bar position ) into human readable strings

'GetWindowStyle' function converts window style integer values into human readable strings

'JSONExplode' function transforms JSON into a return-delimited list similar to YAML
