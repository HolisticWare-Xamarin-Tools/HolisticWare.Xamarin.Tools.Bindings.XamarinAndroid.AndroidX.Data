# Analysis Report

## Bindings Analysis

### Unmanaged 

*   TAR - types Android registered

    *   N = 2733

    *   [./AndroidX.merged.dll.TAR.csv](./AndroidX.merged.dll.TAR.csv)
    
    *   check: N = 2733 = `TARIG.Count()` + `TARNIG.Count()` = 1199 + 1534 = 2733

*   TARIG - types Android registered found in Google's Mappings

    *   N = 1199

    *   [./AndroidX.merged.dll.TARIG.csv](./AndroidX.merged.dll.TARIG.csv)

*   TARNIG - types Android registered NOT found in Google's Mappings

    *   N = 1534

    *   [./AndroidX.merged.dll.TARNIG.csv](./AndroidX.merged.dll.TARNIG.csv)

*   TNAR - types nested Android registered

    *   N = 366

    *   [./AndroidX.merged.dll.TNAR.csv](./AndroidX.merged.dll.TNAR.csv)
    
    *   check: N = 366 = `TNARIG.Count()` + `TNARNIG.Count()` = 294 + 72 = 366

*   TNARIG - types nested Android registered in Google\'s mappings

    *   N = 294

    *   [./AndroidX.merged.dll.TNARIG.csv](./AndroidX.merged.dll.TNARIG.csv)
    
*   TNARNIG - types nested Android registered NOT in Google\'s mappings

    *   N = 72

    *   [./AndroidX.merged.dll.TNARNIG.csv](./AndroidX.merged.dll.TNARNIG.csv)
    
*   TAUR - types Android unregistered 
        
    *   N = 0

    *   [./AndroidX.merged.dll.TAUR.csv](./AndroidX.merged.dll.TAUR.csv)
    
*   TR - type references

    *   N = 503

    *   [./AndroidX.merged.dll.TR.csv](./AndroidX.merged.dll.TR.csv)
    
## Managed 

*   MappingsForMigrationMergeJoin

    *   N = 2518

    *   [./AndroidX.merged.dll.MappingsForMigrationMergeJoin.csv](./AndroidX.merged.dll.MappingsForMigrationMergeJoin.csv)
        
    
## Google Mappings

GoogleMapping = 1936;

### Size Reduction

(android.arch.paging, 1914)
(android.arch.persistence.db, 1902)
(android.arch.persistence.db.framework, 1902)
(android.arch.persistence.room, 1693)
(android.databinding, 1613)
(android.support.test, 1263)


