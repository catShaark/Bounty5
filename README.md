How to create backup secp256k1 and ed25519 pubkeys
1. Run install_gnokey.sh to install gnokey lib <br />
    ```bash install_gnokey.sh```
2. To add secp256k1 key using gnokey and custom entropy <br />
	```gnokey add your_key_name_1 --type secp256k1 --entropy```
   To add ed25519 key using gnokey and custom entorpy <br />
   	```gnokey add your_key_name_2 --type ed25519 --entropy```
   Create multisig key from the the above 2 key <br />
   	```gnokey add your_key_name --multisig your_key_name_1, your_key_name_2```
