# dotnet-get-origin-uid (.NET Core 2.2) / Solution to retrieve UID for Origin.

## To Run:
  1. On your initial run, use getPsnRefreshToken("ticketUuid", "_2fa") to get the value of a refesh_token.
  2. Use the value of the refresh_token to run getPsnUid("user", "refreshToken") from now on (this process can be repeated as necessary).

### Initial Run:
```sh
getPsnRefreshToken("ticketUuid", "_2fa");
Console.ReadKey();
```

### Future Runs:
```sh
getPsnUid("user", "refreshToken");
Console.ReadKey();
```

### 7z Password:
To obtain the password for the 7z, contact kpbant@gmail.com.
