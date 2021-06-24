# Policy script management

The plugin provides a dedicated UI to create and manage policy scripts. These scripts can be used while minting native tokens.

### Create a simple script with single signature

* Click on "Create Script \(Single sig\)" icon
* Select "Generate From". There are three options.
  * **Generate New** : To generate a new secret key, verification key and use that to generate a policy script.
  * **Address**: Use an existing address to generate a policy script
  * **Secret key**: Provide cbor hex of an existing secret key to generate policy script
* Click on "Generate Json" to view the generated policy script, policy id
* Click on "Save" to save policy keys and corresponding key pair in the script store. So that those can be used later.
* \(Optional\) You can also export the generated key pair and policy script as json files.

{% embed url="https://youtu.be/Lsij4OeZb6I" %}

### 

### Create a multisig script with TimeLock

You can create a multi-sig script using individual scripts. You can also add timelock attributes like before and after to that.

* Click on "Create script \(Sigs & TimeLock\) to create a multi-sig script with timelock.

{% embed url="https://youtu.be/C5Q8VUwKESM" %}







