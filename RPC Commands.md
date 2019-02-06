### General usage of the RPC wallet are found in this document. 


### Running the RPC on Command line options:

```

General options:
  --help                                Produce help message
  --version                             Output version information

Wallet options:
  --daemon-address arg                  Use daemon instance at <host>:<port>
  --daemon-host arg                     Use daemon instance at host <arg> 
                                        instead of localhost
  --password arg                        Wallet password (escape/quote as 
                                        needed)
  --password-file arg                   Wallet password file
  --daemon-port arg (=0)                Use daemon instance at port <arg> 
                                        instead of 11181
  --daemon-login arg                    Specify username[:password] for daemon 
                                        RPC client
  --testnet                             For testnet. Daemon must also be 
                                        launched with --testnet flag
  --stagenet                            For stagenet. Daemon must also be 
                                        launched with --stagenet flag
  --restricted-rpc                      Restricts to view-only commands
  --shared-ringdb-dir arg (=/Users/yourname/.shared-ringdb, /Users/yourname/.shared-ringdb/testnet if 'testnet', /Users/yourname/.shared-ringdb/stagenet if 'stagenet')
                                        Set shared ring database path
  --rpc-bind-port arg                   Sets bind port for server
  --disable-rpc-login                   Disable HTTP authentication for RPC 
                                        connections served by this process
  --trusted-daemon                      Enable commands which rely on a trusted
                                        daemon
  --rpc-bind-ip arg (=127.0.0.1)        Specify IP to bind RPC server
  --rpc-login arg                       Specify username[:password] required 
                                        for RPC server
  --confirm-external-bind               Confirm rpc-bind-ip value is NOT a 
                                        loopback (local) IP
  --rpc-access-control-origins arg      Specify a comma separated list of 
                                        origins to allow cross origin resource 
                                        sharing
  --wallet-file arg                     Use wallet <arg>
  --generate-from-json arg              Generate wallet from JSON format file
  --wallet-dir arg                      Directory for newly created wallets
  --prompt-for-password                 Prompts for password when not provided
  --log-file arg                        Specify log file
  --log-level arg                       0-4 or categories
  --max-log-file-size arg (=104850000)  Specify maximum log file size [B]
  --max-log-files arg (=50)             Specify maximum number of rotated log 
                                        files to be saved (no limit by setting 
                                        to 0)
  --max-concurrency arg (=1)            Max number of threads to use for a 
                                        parallel job
  --config-file arg                     Config file

```
  
### Running RPC wallet functions:
  
* TO DO 
  Need to add to this list
