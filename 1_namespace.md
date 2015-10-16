Namespace is used to avoid rewrite to variable confliction.

    var com = com || {};
        com.dong = com.dong || {};
          
    com.dong.dq = function(selector, context) {
        //...
    }
      
    com.dong.dq.loadJS = function() {
        //...
    }
    
