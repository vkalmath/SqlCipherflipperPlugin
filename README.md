# SqlCipherflipperPlugin
Flipper Desktop plugin for https://github.com/sqlcipher/android-database-sqlcipher

This plugin used with Flipper Desktop client to visualize the encrypted DB inside android applications.
The encryped sql DB it works with is https://github.com/sqlcipher/android-database-sqlcipher

Usage steps:
1. Clone the repository
2. run `npm pack` inside the folder which generates cipherdatabases@1.0.1.tgz file.
3. Open the Flipper Desktop client.On left navigatio bar locate ```Manage Plugins``` and click on it
4. switch to install plugins tab
5. click on 3-dots next to empty text box and locate the `cipherdatabases@1.0.1.tgz` which is generated above.
6. Restart the flipper desktop client.


Note: This needs android plugin as well to work.
It can be found here: https://github.com/vkalmath/flipper-sql-cipher-android/blob/master/README.md
