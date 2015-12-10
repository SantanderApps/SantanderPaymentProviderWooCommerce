## Changelog ##

### 1.0.6wo ###
* Changed: Better informative texts in checkout.

### 1.0.5wo ###
* Bug: Fixes a bug with token that is being incorrect encoded when sent to GetResult().

### 1.0.4wo ###
* Bug: Solves an issue with verifying user account details.

### 1.0.3wo ###
* Tested for version 4.4 of WordPress.
* Bug: Return URL did not work when permalinks had another format then ’Default’.
* Removed: Santander\base\sendAndDeletePreviousLog() have never been used and is now removed.

### 1.0.2wo ###
* Fix: syntax error in src/Santander/i18n/Message.php.

### 1.0.1wo ###
* Fix: the logger is trying to chmod log directory if not writeable.

### 1.0.0wo ###
* First stable release