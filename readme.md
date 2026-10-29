//this readme is only friendly to: markdown in plain txt. It is not ready for previews.


this is a human work.

Reason for this
I found a problem when I have to manually calculate every single ip including subnetmasks all times during tutorials in the network fundementals course, so I decided to create this simple Java program using basic IO logic and some mathematical calculations to solve the repeative unnecessary steps 

App Flow

App start
user select drop down
    -mode 1: Find Ip address usable hosts
    -mode 2: Find Ip prefix 
    -mode 3: Find subnet mask address  (prefix is required.)
    -after final output:    t<- Continue mode selection
                            f<- Exit the app.
End App
[-----------------------------------------------------------------------------------------------]
Variable designs (Meaningful names) |                                                           |
VIpAddress          |   double      |   ipv4 address storage                                    |
Prefix_             |   int         |   prefix storage, must be in range of (>0 && <= 32)       |
V4subnetAddress     |   double      |   ipv4 subnet mask address output storage                 |
Variable            |   Type        |   Description                                             |
[-----------------------------------------------------------------------------------------------]
Calculation steps
Finding the ip prefix:
