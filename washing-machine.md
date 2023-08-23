![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1/hw/get/washing-01/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "washing-01",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "114"
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
    "name"      : "get firmware",
    "value"     : "20"
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
    "name"      : "manufacture id",
    "value"     : "A",
    "location"  : "Rayong"
}
```

## Set geo-location or location placement
```
Topic: v1/
Payload: {
    "action"    : "set",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "location",
    "value"     : "Rayong"
}
```

## Monitor machine sensor
```
Topic: v1/
Payload: {
    "action"    : "monitor",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "154"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1/
Payload: {
    "action"    : "set",
    "project"   : "6310301023",
    "model"     : "Washing Machine",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "main"
}
```
