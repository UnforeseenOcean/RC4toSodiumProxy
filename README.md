# Note:
This proxy is outdated since the latest Clash Royale update (2.2). Supercell removed rc4 encryption from the game so the workaround we found doesn't work anymore.

# RC4toSodiumProxy :
A simple Clash Royale proxy

Proxy work like this:<br />
        
        Client ------->   Proxy     -------> Server
               (RC4)    (Convert)   (Sodium)
        Client <-------   Proxy     <------ Server

Run it with:<br />
`python Main.py`

For more information type:<br />
`python Main.py -h`

## Dependencies :
Install `pynacl` with:<br />

     python -m pip install pynacl

Install `pyblake2` with:<br />

     python -m pip install pyblake2

Install `pycryptodome` with:<br />

     python -m pip install pycryptodome

## PS :
You need a patched rc4 apk, here is one there for CR 2.1:<br />
https://mega.nz/#!eEVUmC4a!hfaSup3cC58ffYQrFhU3fUigQX8kaNqMSnDGzBK_ThQ<br />
For more information contact me at @GaLaXy1036#1601
