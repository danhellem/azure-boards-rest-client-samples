# azure-boards-rest-client-samples
REST API samples in VS Code

# Environmental Settings
`
{   
    "rest-client.environmentVariables": {
        "$shared": {              
            "authorization": "Basic [personal access token]"
        },
        "privatepreview": {
            "organization": "[organization name]",
            "project": "[Project name]",
            "authorizationToken": "{{$shared authorization}}"       
        }         
    }      
}
`