---
description: >-
  The EVENT_UNIT_ATTACH push event is sent when an identifier/unit is attached
  to a new call.
---

# Attach Unit

## EVENT\_UNIT\_ATTACH Post

```javascript
{
  "key": "YOUR_API_KEY", // Authenticate legitimate event traffic
  "type": "EVENT_DISPATCH_UNIT_ATTACH",
  "data": {
    "ident": 1,              // (Option 1) Single Identifier/Unit ID
    "idents": [123, 456],    // (Option 2) Multiple Identifiers/Unit IDs
    "callId": 111            // Dispatch Call ID
  }
}
        
```

### Identifier Field Options

The `ident` is a unique number specifying the a unit "identifier" being attached to a call. This field may be replaced with the `idents` array, specifying multiple identifiers being attached to the call at once.

