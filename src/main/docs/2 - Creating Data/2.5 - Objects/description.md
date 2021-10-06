# 2.5 - Objects

Objects are a series of key-value mappings, where the value can be of any type:

---
#### DW Script:
```dw
%dw 2.0
output json
---
%dw 2.0
output json
---
{
"ID_PROJECT_LOCATION" : "344957",
"2132": null,
"2129": null,
"2442": null,
"2131": null,
"2126": "Yes"
}

```
#### Output:
{
"id_project_location": "344957",
"data": [
{
"id_general_detail": "2132",
"value": null
},
{
"id_general_detail": "2129",
"value": null
},
{
"id_general_detail": "2442",
"value": null
},
{
"id_general_detail": "2131",
"value": null
},
{
"id_general_detail": "2126",
"value": "Yes"
}
]
}
---

DataWeave allows repeated keys on Objects as well. This may seem odd, but the support for this makes sense when we consider XML:

---
```
<?xml version='1.0' encoding='UTF-8'?>
<titles>
  <title>Titanic</title>
  <title>Avatar</title>
</titles>
```
---

## Exercise

Use repeated keys to obtain the XML above as output.

> Change the output to be `json`. Are the keys still repeated? Is this valid JSON?
