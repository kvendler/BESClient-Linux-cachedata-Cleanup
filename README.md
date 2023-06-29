# BESClient-Linux-cachedata-Cleanup
Version 0.9

This project is for the purpose of create BigFix content for Linux devices that will provide:

1. An analysis that will report on the amount of disk space being used by /var/opt/BESClient/CITBin/cache-data on Linux clients. This analysis also establishes a threshold for used disk space and measures whether this threshold has been exceeded. (The default threshold is 350 MB, but this can be modified in the Relevance)
   
2.  A fixlet that can be executed against targets to clear out the /var/opt/BESClient/CITBin/cache-data directory
