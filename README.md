# AutofillField
ProcessWire Fieldtype module, auto-fill field from other values on the page when the page is saved.

# Status
Beta

# Compatibility
Works with ProcessWire version 2.7, 2.8 and 3.0.

# Description
This module populates a field's value when the page is saved. Simply create a field and enter
a pattern consisting of arbitrary characters and any of the page's field values in curly braces.

This module is similar in functionality to the official [FieldtypeConcatenate](http://modules.processwire.com/modules/fieldtype-concat/)
module, only that FieldtypeConcatenate generates the new value at runtime while AutofillField
stores the value in the database. Keep in mind that concatenating a lot of field values using
this module could really blow up your database and memory footprint.

Example:

```{title}, {name}```

