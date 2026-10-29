
## this project is pure human work, no ai slop included..
<code>
Reason for this
I found a problem when I have to manually calculate every single ip including subnetmasks all times during tutorials in the network fundementals course, so I decided to create this simple Java program using basic IO logic and some mathematical calculations to solve the repeative unnecessary steps 
</code>

## App Flow
```
    App start
    user select drop down
    -mode 1: Find Ip address usable hosts
    -mode 2s: Find subnet mask address  (prefix is required.)
    -after final output:    t<- Continue mode selection
                            f<- Exit the app.
End App
```
<hr>

//
## Calculation Steps                                                                               
<li>01
    Finding ip address usable hosts:
    NumHostBt = (32 - Prefix_)
    Then
    Fusableb = (2 ** NumHostBt) - 2 <br></li>
<li>02  Finding ipv4 address subnetmask:

    1=128,2=192,3=224,4=240,5=248,6=252,7=254,8=255
</li>