# go-cron
A golang CLI application to help management of cron tasks

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