preventDoubleSubmission
=======================

jQuery Plugin to prevent form double submission.

Use it like this: 
```javascript 
$('form').preventDoubleSubmission(); 
```
If there are AJAX forms that should be allowed to submit multiple times per page load, you can give them a class indicating that, then exclude them from your selector like this:
```javascript 
$('form:not(.js-allow-double-submission)').preventDoubleSubmission(); 
```
