# Simple PHP Blockchain App

A simplified blockchain App in PHP


## Commands

Simple PHP Blockchain App Command List

|Command         |Description                    |Example                        |
|----------------|-------------------------------|-----------------------------|
|createblockchain	|Create new blockchain			| php bc.php createblockchain $uid
|send				|Send coin to someone			| php bc.php send $from $to $amount
|printchain			|Print chain list from database	| php bc.php printchain
|getbalance			|Print Someone Balance 			| php bc.php getbalance $uid

## Detailed Usage
~$ php bc.php createblockchain "utkuhalis"
~$ php bc.php getbalance "utkuhalis"
~$ php bc.php send "from" "to" "amount"
~$ php bc.php printchain