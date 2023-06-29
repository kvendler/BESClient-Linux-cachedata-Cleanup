# BESClient-Linux-cachedata-Cleanup
Version 0.9

This project is for the purpose of creating BigFix content for Linux devices that will provide:

1. An Analysis (Threshold for BESClient_CITBin_cache_data for Linux Devices.bes) that will report on the amount of disk space being used by /var/opt/BESClient/CITBin/cache-data on Linux clients. This analysis also establishes a threshold for used disk space and measures whether this threshold has been exceeded. (The default threshold is 350 MB, but this can be modified in the Relevance)
   
2.  A Fixlet (Clear Cache for BESClient_CITBin_cache_data_.bes) that can be executed against targets to clear out the /var/opt/BESClient/CITBin/cache-data directory. This Fixlet will be relevant for any Linux device where the cache-data folder is 350 MB in size or greater.
