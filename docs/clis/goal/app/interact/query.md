title: goal app interact query
---
## goal app interact query



Query local or global state from an application



### Synopsis



Query local or global state from an application



```

goal app interact query [flags]

```



### Options



```

      --app-id uint   Application ID

  -f, --from string   Account to query state for (if omitted, query from global state)

  -h, --help          help for query

```



### Options inherited from parent commands



```

      --app-account strings        Accounts that may be accessed from application logic

      --app-arg stringArray        Args to encode for application transactions (all will be encoded to a byte slice). For ints, use the form 'int:1234'. For raw bytes, use the form 'b64:A=='. For printable strings, use the form 'str:hello'. For addresses, use the form 'addr:XYZ...'.

  -i, --app-input string           JSON file containing encoded arguments and inputs (mutually exclusive with app-arg-b64 and app-account)

      --approval-prog string       (Uncompiled) TEAL assembly program filename for approving/rejecting transactions

      --approval-prog-raw string   Compiled TEAL program filename for approving/rejecting transactions

      --clear-prog string          (Uncompiled) TEAL assembly program filename for updating application state when a user clears their local state

      --clear-prog-raw string      Compiled TEAL program filename for updating application state when a user clears their local state

  -d, --datadir stringArray        Data directory for the node

      --foreign-app strings        Indexes of other apps whose global state is read in this transaction

      --foreign-asset strings      Indexes of assets whose parameters are read in this transaction

      --header string              Application header

  -k, --kmddir string              Data directory for kmd

  -w, --wallet string              Set the wallet to be used for the selected operation

```



### SEE ALSO



* [goal app interact](../../interact/interact/)	 - Interact with an application



