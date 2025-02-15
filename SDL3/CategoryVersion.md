
# Querying SDL Version

'''Include File(s):''' [http://hg.libsdl.org/SDL/file/default/include/SDL_version.h SDL_version.h], [http://hg.libsdl.org/SDL/file/default/include/SDL_revision.h SDL_revision.h]


## Introduction

These functions are used to collect or display information about the version of SDL that is currently being used by the program or that it was compiled against.

: The version consists of three segments (X.Y.Z)
* X = '''Major Version''', which increments with massive changes, additions, and enhancements
* Y = '''Minor Version''', which increments with backwards-compatible changes to the major revision
* Z = '''Patchlevel''', which increments with fixes to the minor revision<br/>
 ''Example:'' The first version of SDL 2 was 2.0.0

: The version may also be reported as a 4-digit numeric value where the thousands place represents the major version, the hundreds place represents the minor version, and the tens and ones places represent the patchlevel (update version).
 ''Example:'' The first version number of SDL 2 was 2000

SDL_revision.h must be included in your program explicitly if you want to use the SDL_REVISION constant.

<!-- #Remove this line and the ## below to use this markup if it becomes relevant to this category -->
<!-- #== Enumerations == -->
<!-- #<<FullSearchCached(category:CategoryEnum CategoryVersion -title:SGEnumerations)>> -->

## Structures
<<FullSearchCached(category:CategoryStruct CategoryVersion -title:SGStructures)>>

## Functions
<<FullSearchCached(category:CategoryVersion -CategoryStruct -CategoryEnum -title:SGFunctions)>>

<!-- BEGIN CATEGORY LIST -->
- [SDL_COMPILEDVERSION](SDL_COMPILEDVERSION)
- [SDL_GetRevision](SDL_GetRevision)
- [SDL_GetVersion](SDL_GetVersion)
- [SDL_REVISION](SDL_REVISION)
- [SDL_version](SDL_version)
- [SDL_VERSION_ATLEAST](SDL_VERSION_ATLEAST)
- [SDL_VERSIONNUM](SDL_VERSIONNUM)
<!-- END CATEGORY LIST -->
----
CategoryCategory
