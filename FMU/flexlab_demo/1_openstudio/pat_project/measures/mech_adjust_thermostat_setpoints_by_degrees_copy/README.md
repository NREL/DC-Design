

###### (Automatically generated documentation)

# Adjust Thermostat Setpoints by Degrees Copy

## Description
This measure adjusts heating and cooling setpoints by a user specified number of degrees. This is applied throughout the entire building.

## Modeler Description
This measure will clone all of the schedules that are used as heating and cooling setpoints for thermal zones. The clones are hooked up to the thermostat in place of the original schedules. Then the schedules are adjusted by the specified values. There is a checkbox to determine if the thermostat for design days should be altered.

## Measure Type
ModelMeasure

## Taxonomy


## Arguments


### Degrees Fahrenheit to Adjust Cooling Setpoint By

**Name:** cooling_adjustment,
**Type:** Double,
**Units:** ,
**Required:** true,
**Model Dependent:** false

### Degrees Fahrenheit to Adjust heating Setpoint By

**Name:** heating_adjustment,
**Type:** Double,
**Units:** ,
**Required:** true,
**Model Dependent:** false

### Alter Design Day Thermostats

**Name:** alter_design_days,
**Type:** Boolean,
**Units:** ,
**Required:** true,
**Model Dependent:** false

### Adjust ScheduleRules?

**Name:** adjust_schedule_rules,
**Type:** Boolean,
**Units:** ,
**Required:** true,
**Model Dependent:** false

### Adjust default schedule?

**Name:** adjust_default,
**Type:** Boolean,
**Units:** ,
**Required:** true,
**Model Dependent:** false




