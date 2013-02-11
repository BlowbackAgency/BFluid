# B.Fluid Grid System
B.Fluid is a flexible css/less grid system based on classic 960.gs syntax. We have fluid CSS-grids for 10/12/16 column tables to use when developing just with pure css. For CSS Preprocessing junkies we offer powerfull less mixin that generates fluid and fixed width grids on the fly.

**Quick example:**
```css
@import "bfluid.less";
/* 12 column fuild grid based on default settings */
#grid > .fluid(12);
/* 12 column fuild grid based on 960px width and 20px gutters */
#grid > .fluid(12,0,0,20,0,960);
/* 10, 12 and 16 column fuild grids based on 1000px width and 30px gutters and 30px padding */
#grid > .fluid(10,12,16,30,30,1000);
```

More info and documentation coming soon..

**License:** GNU Public License (GPL) http://www.gnu.org/copyleft/gpl.html