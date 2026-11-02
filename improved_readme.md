# Better flowChart for the concept in peseudo code 


START APP
    GET INPUT <- User_Select_Mode
    Switch (x)
        case 1:
            GET INPUT <- CIDR_Prefix
            int HostPortion <- 32 - CIDR_Prefix
            DISPLAY <- "Host portion" + HostPortion
            IF Continue <- y
                return <- GET INPUT User_Select_Mode
            ELSE
                END APP 
        case 2:
            GET INPUT <- TotalHostBits
            