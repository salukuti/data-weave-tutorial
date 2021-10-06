# 3.6 - Challenge

Use what you know about selectors to get the output specified below from this input data.

---
#### Input:
```json
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
```json
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

- Does the descendant selector select all the keys or just the first one in a nested Object?
- Does the multi-value selector select keys on nested levels of the Object?
- What happens if you combine both descendant and multi-value selectors (`..*`)?
