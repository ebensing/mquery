
0.1.1 / 2013-06-24
==================

  * fixed; $intersects -> $geoIntersects #14 [ebensing](https://github.com/ebensing)
  * fixed; Retain key order when copying objects #15 [ebensing](https://github.com/ebensing)
  * bump mongodb dev dep

0.1.0 / 2013-05-06
==================

  * findAndModify; return the query
  * move mquery.proto.canMerge to mquery.canMerge
  * overwrite option now works with non-empty objects
  * use strict mode
  * validate count options
  * validate distinct options
  * add aggregate to base collection methods
  * clone merge arguments
  * clone merged update arguments
  * move subclass to mquery.prototype.toConstructor
  * fixed; maxScan casing
  * use regexp-clone
  * added; geometry/intersects support
  * support $and
  * near: do not use "radius"
  * callbacks always fire on next turn of loop
  * defined collection interface
  * remove time from tests
  * clarify goals
  * updated docs;

0.0.1 / 2012-12-15
==================

  * initial release
