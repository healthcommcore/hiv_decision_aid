Things to do when transferring from build to Drupal module:
- change all json loading paths from ./js to sites/all/modules/custom/prep_decision_aid/js
- change $.get to jQuery.get
- make sure css file named prep_style, not style
- include all json files, put in same directory as main up_app.js file
- include index.css file for rc-slider component to work properly
