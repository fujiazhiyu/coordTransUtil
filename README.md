# coordTransUtil
坐标转换, WGS84 GCJ-02 BD-09 互转. python &amp; js

## 用法

### python

    from coordTransUtil.coordTransform_utils import wgs84_to_gcj02
    
    # @return [lng, lat]
    wgs84_to_gcj02(lng, lat)
    
### javascript

    import * as coordTransform_utils from './coordTransUtil/coordTransform_utils.js';
    
    # @return [lng, lat]
    coordTransform_utils.wgs84_to_gcj02(lng, lat)
