# Analysis Report

## Bindings Analysis

### Unmanaged 

*   TAR - types Android registered

    *   N = 2827

    *   [./Android.Support.merged.dll.TAR.csv](./Android.Support.merged.dll.TAR.csv)
    
    *   check: N = 2827 = `TARIG.Count()` + `TARNIG.Count()` = 1251 + 1576 = 2827

*   TARIG - types Android registered found in Google's Mappings

    *   N = 1251

    *   [./Android.Support.merged.dll.TARIG.csv](./Android.Support.merged.dll.TARIG.csv)

*   TARNIG - types Android registered NOT found in Google's Mappings

    *   N = 1576

    *   [./Android.Support.merged.dll.TARNIG.csv](./Android.Support.merged.dll.TARNIG.csv)

*   TNAR - types nested Android registered

    *   N = 375

    *   [./Android.Support.merged.dll.TNAR.csv](./Android.Support.merged.dll.TNAR.csv)
    
    *   check: N = 375 = `TNARIG.Count()` + `TNARNIG.Count()` = 291 + 84 = $SUM_TNAR$

*   TNARIG - types nested Android registered in Google\'s mappings

    *   N = 291

    *   [./Android.Support.merged.dll.TNAR.csv](./Android.Support.merged.dll.TNARIG.csv)
    
*   TNARNIG - types nested Android registered NOT in Google\'s mappings

    *   N = 84

    *   [./Android.Support.merged.dll.TNAR.csv](./Android.Support.merged.dll.TNARNIG.csv)
    
*   TAUR - types Android unregistered 
        
    *   N = 0

    *   [./Android.Support.merged.dll.TAUR.csv](./Android.Support.merged.dll.TAUR.csv)
    
*   TR - type references

    *   N = 508

    *   [./Android.Support.merged.dll.TR.csv](./Android.Support.merged.dll.TR.csv)
    
## Managed 

*   MappingsForMigrationMergeJoin

    *   N = 2574

    *   [./Android.Support.merged.dll.MappingsForMigrationMergeJoin.csv](./Android.Support.merged.dll.MappingsForMigrationMergeJoin.csv)
        
    
## Google Mappings

GoogleMapping = 1936;

### Size Reduction

(android.arch.paging, 1914)
(android.arch.persistence.db, 1902)
(android.arch.persistence.db.framework, 1902)
(android.arch.persistence.room, 1693)
(android.databinding, 1613)
(android.support.test, 1263)


