**Note: this is NOT the official branch! I just created a fork to keep track of personal modifications.**

Personal notes:

Remember adding files in WTL and tinyxml

Compilation works without errors using Visual Studio 2010 Pro (Express does not include ATL by default) on Win 8/10, but there seem to be problems with automatic IAT search. 

For Scylla and tinyxml projects: Configuration Properties->General->Platform Toolset-> v100
