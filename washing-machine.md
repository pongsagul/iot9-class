# Washing machine state

## START
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "FILLWATER"
}

## HEATWATER
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "HEATWATER"
}

## WASH
topic:v1cdti/app/get/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "WASH"
}

## RINSE
topic:v1cdti/app/get/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/app/get/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "state",
    "value"     :   "SPIN"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "DOORCLOSE",
    "value"     :   "value"
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "WATERFULLLEVEL",
    "value"     :   "value"
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "TEMPERATUREREACHED",
    "value"     :   "value"
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/get/1212312121/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "MOTORFAILURE"
}

## FAULTCLEARED
topic:v1cdti/app/set/6310301003/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301003",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "FAULTCLEARED"
}