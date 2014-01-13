bootstrap-notify
================

Bootstrap alert system made better.

# usage

~~~javascript
$('#notify').notify({
    message: {
        html: '<h4>Error message</h4>'
    },
    type: 'danger',
    fadeOut: {
      enabled: true,
      delay: 3000
    }
}).show();
~~~

###notice

    type: `error` in bootstrap 3 becomes `danger`

