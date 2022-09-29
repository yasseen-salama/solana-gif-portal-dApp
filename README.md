# Solana GIF Portal dApp

A [_buildspace](https://buildspace.so/) project to build a GIF dApp on the Solana blockchain using Rust and JavaScript. 

## Test
to run the test on `devnet` run `anchor test` on `tests/myepicproject.js`

## Deploy
to deploy run `anchor deploy` \
\
Don't forget toupdate the IDL file on the web app: 
```
anchor idl upgade -f target/idl/myepicproject.json `solana address -k target/deploy/myepicproject-keypair.json`
```



## Program Id
[QGwSEkdoSWSHBRn5eA31miyfQ5wPXGi9L63pcX73QcK](https://explorer.solana.com/address/QGwSEkdoSWSHBRn5eA31miyfQ5wPXGi9L63pcX73QcK?cluster=devnet&utm_source=buildspace.so&utm_medium=buildspace_project)


