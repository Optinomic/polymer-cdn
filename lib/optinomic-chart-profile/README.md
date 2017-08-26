# \<optinomic-chart-profile\>

`optinomic-chart-profile` creates awesome Chart-Profiles. Designed for Optionmic-Apps.

## Porperties - Descripiton
### Options

#### Example

```JAVASCRIPT
var options = {
    "min": "auto",
    "max": "auto",
    "item_height": 50,
    "item_text_left": 100,
    "item_text_right": 120,
    "color_skin": "default",
    "color_grid": "#9E9E9E",
    "color_clinic_sample": "#673AB7",
    "show_baseline": true,
    "show_scale_text": true,
    "show_score_vertical_line": false,
    "show_score_profile_line": true,
    "show_score_circles": true,
    "range_alpha": 0.1,
    "vertical_grid_every_x": 1,
    "response_title_path": "calculation.info.mz.mz_typ",
    "response_date_path": "calculation.info.filled"
};
```

#### Details
| Property  |  Description  |
|:---:|---|
| __min__ | "auto" will find the min/max automatically for you. You can also hardcode the min or max by setting it as a number. _Default: "auto"_ |
| __max__ | "auto" will find the min/max automatically for you. You can also hardcode the min or max by setting it as a number. _Default: "auto"_ |
| __item_height__ | The height (px) of every scale from scales. _Default: 50_ |
"color_skin"_ |
| __color_skin__ | measurements colors skin. Possible values so far are: default, zebra, pink_dark_to_light, indigo_dark_to_light, grey_dark_to_light _Default: 'default'_ |
