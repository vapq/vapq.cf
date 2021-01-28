    <script src= 
"https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"> 
    </script> 
  
    <script> 
        $.getJSON("https://api.ipify.org?format=json", 
                                          function(data) { 
  
            // Setting text of element P with id gfg 
            $("#ip").html(data.ip); 
        }) 
    </script> 
    
# Debugging at Vapq, your IP has been listed below due to being in debug mode.
<p id="ip"></p>
