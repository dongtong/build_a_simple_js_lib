Creating self-invoking anonymous function and add private variables.

      (function() {
          var version = '1.00';
          console.log('version: ', version);
      }());
      
      console.log(version);
      
  Because in ES5, JavaScript scope is functional, so private variable is in function.
