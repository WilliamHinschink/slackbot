https://api.slack.com/apps

Create App on Workspace

Enable Events -> true

Insert URL of the API bot

on Subscribe to bot events add Bot User Event
    message.channels -> public
    message.groups -> private
    

On OAuth & Permissions
    Copy Bot User OAuth Token
    Add Scopes an OAuth Scope
        chat:write
        groups:history
        channels:history
        

on Basic Information
    Copy Signing Secret
