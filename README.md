# smash-exp

An exploit to get unlimited xp and coins in https://smashkarts.io/


## Help
```
options:
  -h, --help            show this help message and exit

Authentication Options (Required):
  -e EMAIL, --email EMAIL
                        Email address.
  -p PASSWORD, --password PASSWORD
                        Password.
  --token TOKEN         Authentication token.
  -s, --signup          Perform signup instead of login.

Action Flag:
  --update              Flag to initiate the stats update action.

Stats (used with --update):
  --coins COINS         Total Coins to add (batched in 2000 increments, default: 0)
  --xp XP               Total XP to add (batched in 2000 increments, default: 0)
```

## Getting the Token

If you are using Google Sign-In or Apple Sign-In, you need to provide a token.

1.  Open the developer tools in your browser (e.g., Chrome DevTools).
2.  Go to the Network tab.
3.  Filter for requests to `us-central1-webgltest-17af1.cloudfunctions.net`.
4.  Find a request with an `Authorization` header.
5.  The token is the value of the `Authorization` header, starting with `Bearer `. Copy the token value (without `Bearer `).


**P.S: I tried to reach the developers but they didnt responded**