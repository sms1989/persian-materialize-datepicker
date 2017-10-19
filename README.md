# persian-materialize-datepicker
this is jalaali (persian) calendar for materilizecss. extended from materilize native datepicker

# How to use
you can add js file to your project and call ppickadate for persian datepicker

### Simple Example
```
$('.pdatepicker').ppickadate({
    selectMonths: true, // Creates a dropdown to control month
    selectYears: 15, // Creates a dropdown of 15 years to control year,
    closeOnSelect: false, // Close upon selecting a date,
});
```

### Settings
all settings like [materialize](http://materializecss.com/forms.html#date-picker) but we have a new setting ```gregorianReturn``` as boolian for return gregorian date;

```
 $('.pdatepicker').ppickadate({
    selectMonths: true, // Creates a dropdown to control month
    selectYears: 15, // Creates a dropdown of 15 years to control year,
    closeOnSelect: false, // Close upon selecting a date,
    gregorianReturn: true //Default is false
});
```

### Persian number
for persian number you can use another plugin [Persian number jQuery plugin](https://github.com/sms1989/persian-numbers-jquery-plugin)