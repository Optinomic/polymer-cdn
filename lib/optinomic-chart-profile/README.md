# \<optinomic-chart-profile\>

`optinomic-chart-profile` creates awesome Chart-Profiles. Designed for Optionmic-Apps.

## Porperties - Descripiton

### Options

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
    "show_settings_block": true,
    "show_ranges_overview": true,
    "allow_toggle_settings_block": false,
    "range_alpha": 0.1,
    "vertical_grid_every_x": 1,
    "norm_sample": "Z-Werte wurden aufgrund der Normstichprobe nach Franke (2000) berechnet (N=300).",
    "response_title_path": "calculation.info.mz.mz_typ",
    "response_date_path": "calculation.info.filled",
    "dropout": "calculation.info.mz.dropout",
    "dropout_reason": "calculation.info.mz.dropout_reason"
};
```

### Start

```JAVASCRIPT

var start = {
    "left_title": "Geringe Ausprägung",
    "left_text": "Eine längere Beschreibung bzgl. der geringen Ausprägung.",
    "left_color": "#4CAF50",
    "right_title": "Starke Ausprägung",
    "right_text": "Eine längere Beschreibung der starken Ausprägung kann hier gesetzt werden.",
    "right_color": "#F44336"
}
```


#### Details
| Property  |  Description  |
|:---:|---|
| __min__ | "auto" will find the min/max automatically for you. You can also hardcode the min or max by setting it as a number. _Default: "auto"_ |
| __max__ | "auto" will find the min/max automatically for you. You can also hardcode the min or max by setting it as a number. _Default: "auto"_ |
| __item_height__ | The height (px) of every scale from scales. _Default: 50_ |
| __color_skin__ | measurements colors skin. Possible values so far are: `default`, `zebra`, `pink_dark_to_light`, `indigo_dark_to_light`, `grey_dark_to_light`  _Default: 'default'_ |
| __show_settings_block__ | Should the elemet render the Settings-Tab? Bei `false` wird die Übersicht der Messungen angezeigt. _Default: True_ |
| __allow_toggle_settings_block__ | Darf der User zwischen Übersicht und "Settings-Tab" hin und herwechseln? _Default: True_ |
| __response_title_path__ | Path to value: Expects a `String` - How should the measurement be called?  |
| __response_date_path__ | Path to value: Expects a `String` - What ist the date of the measurment?  |
| __dropout__ | Path to value: Expects a `boolean` - Is this measurement a dropout?  |
| __dropout_reason__ | Path to value:: Expects a `String` - Reason for the dropout?  |
