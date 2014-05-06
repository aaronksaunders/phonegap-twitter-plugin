Phonegap Twitter/Facebook Plugin for IOS


The application currently hard codes the facebook application id instead of
passing it inas a parameter.

This must be updated or facebook connectivity will not work

    // Specify App ID and permissions
    NSDictionary *fbOptions = @{
          ACFacebookAppIdKey: @"--- REPLACE ME---",
          ACFacebookPermissionsKey: @[@"email"],
          ACFacebookAudienceKey: ACFacebookAudienceFriends
    };