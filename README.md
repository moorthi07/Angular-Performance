# Angular-Performance
 


### Performance comparision between Angular 2 and Angular 4 (ng2 vs ng4)

### Summary
This is a comparision of angular 2 project ported to angular 4.
- Intalled 4.0 packages
- Changed Material design to beta-3 and removed materialmodule, materialrootmodule
- Imported animation separately

### Angular 4 ( Ng4 )
-Requests: 12 
-Transferred: 5.3 MB  
-Finish: 3.66s
-DOMContentLoaded 3.57 s
-Load: 3.92s

[HAR for NG4](/angular4-har)

![Alt text](/ng4_performance.PNG)

### Angular 2 ( Ng2 )
-Requests: 12
-Transferred: 6.1 
-Finish: 4.82s
-DOMContentLoaded: 4.55 s
-Load: 4.06 s

[HAR for NG2](/angular2-har)
![Alt text](/ng2_performance.PNG)

### ANGULAR 4 Reduced the size about 1 MB and the Load time about .50 s
