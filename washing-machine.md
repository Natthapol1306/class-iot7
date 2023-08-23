![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1/hw/get/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "154"
}
```

## Get firmware version
```
Topic: v1/
Payload: {
    "action"    : "get",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1/
Payload: {
    "action"    : "get",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Set geo-location or location placement
```
Topic: v1/
Payload: {
    "action"    : "get",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Monitor machine sensor
```
Topic: v1/
Payload: {
    "action"    : "get",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1/
Payload: {
    "action"    : "get",
    "project"   : "63103010231",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
}
```
