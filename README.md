# go-cron
A golang cli application to help management of cron tasks. It uses [urfave's cli](https://github.com/urfave/cli) library to aid in creating and parsing parameters for all the cli commands.

## Instalation

## Usage

You can list cron jobs

	$ go-cron list
	Available cron jobs:
	    (1) * * * * * /cron/command
	    (2) * */2 * * * /another/cron/command

You can run a specific cron job

	$ go-cron run 1 
	Running cron command (1) * * * * * /cron/command
	
## TO DO
    * add cron command