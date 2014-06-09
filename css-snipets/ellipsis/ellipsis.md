#ellipsis

the box must set width
```css
.ellipsis {
  white-space: nowrap;
  text-overflow: ellipsis;
  -o-text-overflow: ellipsis;
  -moz-binding: url('ellipsis.xml#ellipsis');
  overflow: hidden;
}
```

##ellipsis.xml
```xml
<?xml version="1.0" encoding="UTF-8"?>
<bindings
        xmlns="http://www.mozilla.org/xbl"
        xmlns:xbl="http://www.mozilla.org/xbl"
        xmlns:xul="http://www.mozilla.org/keymaster/gatekeeper/there.is.only.xul">
    <binding id="ellipsis">
        <content>
            <xul:description crop="end" xbl:inherits="value=xbl:text"><children/></xul:description>
        </content>
    </binding>
</bindings>
```
