# Analysis Report

## Bindings Analysis

### Unmanaged 

*   TAR - types Android registered

    *   N = 2827

    *   [./AndroidSupport.Merged.dll.TAR.csv](./AndroidSupport.Merged.dll.TAR.csv)
    
    *   check: N = 2827 = `TARIG.Count()` + `TARNIG.Count()` = 1252 + 1575 = 2827

*   TARIG - types Android registered found in Google's Mappings

    *   N = 1252

    *   [./AndroidSupport.Merged.dll.TARIG.csv](./AndroidSupport.Merged.dll.TARIG.csv)

*   TARNIG - types Android registered NOT found in Google's Mappings

    *   N = 1575

    *   [./AndroidSupport.Merged.dll.TARNIG.csv](./AndroidSupport.Merged.dll.TARNIG.csv)

*   TARNIGF - types Android registered NOT found in Google's Mappings FIXED 

    *   FIXED - containing type found in Google's Mappings

    *   N = $NTARNIGF$

    *   [./AndroidSupport.Merged.dll.TARNIGF.csv](./AndroidSupport.Merged.dll.TARNIGF.csv)

*   TNAR - types nested Android registered

    *   N = 375

    *   [./AndroidSupport.Merged.dll.TNAR.csv](./AndroidSupport.Merged.dll.TNAR.csv)
    
    *   check: N = 375 = `TNARIG.Count()` + `TNARNIG.Count()` = 291 + 84 = 375

*   TNARIG - types nested Android registered in Google\'s mappings

    *   N = 291

    *   [./AndroidSupport.Merged.dll.TNARIG.csv](./AndroidSupport.Merged.dll.TNARIG.csv)
    
*   TNARNIG - types nested Android registered NOT in Google's mappings

    *   N = 84

    *   [./AndroidSupport.Merged.dll.TNARNIG.csv](./AndroidSupport.Merged.dll.TNARNIG.csv)
    
*   TNARNIGF - types nested Android registered NOT in Google's mappings FIXED

    *   FIXED - containing type found in Google's Mappings
    
    *   N = $NTNARNIGF$

    *   [./AndroidSupport.Merged.dll.TNARNIGF.csv](./AndroidSupport.Merged.dll.TNARNIGF.csv)
    
*   TAUR - types Android unregistered 
        
    *   N = 0

    *   [./AndroidSupport.Merged.dll.TAUR.csv](./AndroidSupport.Merged.dll.TAUR.csv)
    
*   TR - type references

    *   N = 508

    *   [./AndroidSupport.Merged.dll.TR.csv](./AndroidSupport.Merged.dll.TR.csv)
    
## Managed 

*   MappingsForMigrationMergeJoin

    *   N = 3202

    *   [./AndroidSupport.Merged.dll.MappingsForMigrationMergeJoin.csv](./AndroidSupport.Merged.dll.MappingsForMigrationMergeJoin.csv)
        
    
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


