# 7.6 - Challenge

Use the functions you just learned and the concatenation function `++` to work with the payload below so that the missing `dayOfWeek` field is included in each event and only events organized by Ross are shown.

As an example, you can see how a `datetime` value is converted to a `LocalDateTime` and date decomposition used to obtain a day of the week from 1 to 7 and then mapped to the desired name.

---
#### Input
```
{
"ID_PROJECT_LOCATION" : "344957",
"2132": null,
"2129": null,
"2442": null,
"2131": null,
"2126": "Yes"
}
```
#### Output
```
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
```
