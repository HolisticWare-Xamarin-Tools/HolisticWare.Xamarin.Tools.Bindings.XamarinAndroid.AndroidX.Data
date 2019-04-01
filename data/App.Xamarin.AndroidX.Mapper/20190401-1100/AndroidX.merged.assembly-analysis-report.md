# Analysis Report

## Bindings Analysis

### Unmanaged 

*   TAR - types Android registered

    *   N = 2891

    *   [./AndroidX.Merged.dll.TAR.csv](./AndroidX.Merged.dll.TAR.csv)
    
    *   check: N = 2891 = `TARIG.Count()` + `TARNIG.Count()` = 1283 + 1608 = 2891

*   TARIG - types Android registered found in Google's Mappings

    *   N = 1283

    *   [./AndroidX.Merged.dll.TARIG.csv](./AndroidX.Merged.dll.TARIG.csv)

*   TARNIG - types Android registered NOT found in Google's Mappings

    *   N = 1608

    *   [./AndroidX.Merged.dll.TARNIG.csv](./AndroidX.Merged.dll.TARNIG.csv)

*   TARNIGF - types Android registered NOT found in Google's Mappings FIXED 

    *   FIXED - containing type found in Google's Mappings

    *   N = $NTARNIGF$

    *   [./AndroidX.Merged.dll.TARNIGF.csv](./AndroidX.Merged.dll.TARNIGF.csv)

*   TNAR - types nested Android registered

    *   N = 384

    *   [./AndroidX.Merged.dll.TNAR.csv](./AndroidX.Merged.dll.TNAR.csv)
    
    *   check: N = 384 = `TNARIG.Count()` + `TNARNIG.Count()` = 299 + 85 = 384

*   TNARIG - types nested Android registered in Google\'s mappings

    *   N = 299

    *   [./AndroidX.Merged.dll.TNARIG.csv](./AndroidX.Merged.dll.TNARIG.csv)
    
*   TNARNIG - types nested Android registered NOT in Google's mappings

    *   N = 85

    *   [./AndroidX.Merged.dll.TNARNIG.csv](./AndroidX.Merged.dll.TNARNIG.csv)
    
*   TNARNIGF - types nested Android registered NOT in Google's mappings FIXED

    *   FIXED - containing type found in Google's Mappings
    
    *   N = $NTNARNIGF$

    *   [./AndroidX.Merged.dll.TNARNIGF.csv](./AndroidX.Merged.dll.TNARNIGF.csv)
    
*   TAUR - types Android unregistered 
        
    *   N = 0

    *   [./AndroidX.Merged.dll.TAUR.csv](./AndroidX.Merged.dll.TAUR.csv)
    
*   TR - type references

    *   N = 509

    *   [./AndroidX.Merged.dll.TR.csv](./AndroidX.Merged.dll.TR.csv)
    
## Managed 

*   MappingsForMigrationMergeJoin

    *   N = 3275

    *   [./AndroidX.Merged.dll.MappingsForMigrationMergeJoin.csv](./AndroidX.Merged.dll.MappingsForMigrationMergeJoin.csv)
        
    
## Google Mappings

GoogleMapping = 1937;

### Size Reduction

(android.arch.paging, 1915)
(android.arch.persistence.db, 1903)
(android.arch.persistence.db.framework, 1903)
(android.arch.persistence.room, 1694)
(android.databinding, 1614)
(android.support.test, 1264)


## Artifacts for downloads

AndroidX: 

*   https://dev.azure.com/xamarin/public/_build/results?buildId=517

*   https://github.com/xamarin/AndroidSupportComponents/commit/35c1e15052f0f2f2ef6088ced006e959508d97b7

Android Support: 

*   https://dev.azure.com/xamarin/public/_build/results?buildId=578&view=results

*   https://github.com/xamarin/AndroidSupportComponents/commit/df95df2721031fc533e29e39059517757010d432


