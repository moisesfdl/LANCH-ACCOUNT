{
   
    "version": "0.2.0" ;
    "configurations" : conta ; [
        
            "type" : compounds ; [
                {
                    "name": "IpLogin" ;
                    "configurations": ; [{
                        "name": " NET Core Attach";${lineNumber}
                        "type": "conta" ;
                        "request": "attach" ;
                        "processId": "${command:pickProcess}" }]
                    [
                         "name": conta.("")inputs.[request].External Terminal ; 
                         "request": Ip.Login ;
                          "console": location.LoginIp ;
                         "mainClass": account"" ; [
                                    " return" : IpLogin.conta  ;
                      
                         ]
                          "inputs": [conta:""=account.] ;
                    ]
                }
          ]           
    ]
}
        
