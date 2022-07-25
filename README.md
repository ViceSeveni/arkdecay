# arkdecay
Checks BattleMetrics for your last logged in times to specified Ark Survival Evolved Servers.


<h3>Instructions:</h3>

-Pip install "requests" and "beautifulsoup4" if you do not have it.

-You must create a .csv file with your preferred servers' battlemetrics numbers.

-For example, "https://www.battlemetrics.com/servers/ark/7452428" is the link for KnightsGG's Ragnarok server.

-Cut the numbers from the end of the link (7452428, in this example) and enter "Ragnarok, 7452428" into the csv file.

-Repeat this process for all of the servers you wish to have the program check.

-Go to the csv files location, hold shift, right click, and click "copy as path"

-Insert the csv's file path into the server_file variable in the main program, removing "INSERT PATH HERE"

-Make sure to remove the extra quotation marks from the copied file path, or you will get an error.

-At this point you can just save the main program, press win + r, and type "arkdecay" or whatever you named the main program, and it should run no problem.
