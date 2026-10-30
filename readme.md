<div  style="background: linear-gradient(0deg, #024870 0%, #271d35 25%); color: white; padding: 20px; ">

## This project is made with a real human to solve problems.

>Reason for this
I found a problem when I have to manually calculate every single ip including subnetmasks all times during tutorials in the network fundementals course, so I decided to create this simple Java program using basic IO logic and some mathematical calculations to solve the repeative unnecessary steps , by this, I've learnt how to customize more in markdownfiles, such as gradients, and tables!


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

## PeseudoCode Flow


```
Input:
HostUsable, GivenPrefix, SubMskAddress, OutSubMskAddress
Process:

START V4Calc
    FUNCTION USER_SELECT_MODE()   {
        case USER_SELECT_MODE == 1 <- mode 1 ()
        case USER_SELECT_MODE == EXIT_APP ()
    } 
    FUNCTION mode_1() {
        INPUT Ipv4Prefix
        TotalHostBits <- 2 ** Ipv4Prefix 
        DISPLAY "Total usable host bits = " + TotalHostBits
        ASK Option
        ["Want to convert find another host bits ?"] / ["NO"]  
        IF Option == ["Want to convert find another host bits ?"] = ["YES"]
        RETURN USER_SELECT_MODE()
    }
    FUNCTION EXIT_APP() {
        IF Option == ["NO"]
        QUIT APP
    }
END V4Calc  
```

<hr>


| Variables        | Description                           |
| :--------------- | :------------------------------------ |
| User_Select_Mode | Select program mode                   |
| Ipv4Prefix       | Variable storage for Ipv4 prefix      |
| TotalHostBits    | Variable storage for Total host bits  |
| Option           | Requesting user information after end |

**<hr>**