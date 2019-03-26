# dotnet-get-origin-uid (.NET Core 2.2) / Solution to retrieve UID for Origin.

## To Run:
 1. On your initial run, use getOriginAccessToken("email", "password") to get the value of an access_token.
 2. Use the value of the access_token to run getOriginUid("user", "accessToken") from now on (this process can be repeated as necessary).

### Initial Run:
```sh
getOriginAccessToken("email", "password");
Console.ReadKey();
```

### Future Runs:
```sh
getOriginUid("user", "accessToken");
Console.ReadKey();
```

### 7z Password:
To obtain the password for the 7z, contact kpbant@gmail.com.
