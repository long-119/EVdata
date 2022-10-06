# EVdata
Includes the number of EVs for 14 days and specific information about each EV for a random day in the 5 BSSs


## the number of EVs for 14 days
> The folder includes 5 files, each file recordes the number of EVs for each hour of the 14 day.
the ***date*** is from 6/20/2022 to 7/3/2022, and the ***hour*** is from 0 to 24 o 'clock.


## All_EVs
> The file contains all EVs information for the 5 BSSs on a random day, such as the arrival time, the departure time, the operating time, the waiting time, the start charging time, the finish charging time, and so on.

> The meaning of the header in the first row of the table is as follows:

BSS_id | EV_id | arr_T | oper_T | wait_T | spots_id | dep_T | charger_id | start_T | finish_T | SOC | SOH | load_ratio|
------ | ------ | ------ | ------ |------ |------ |------ |------ |------ |------ |------ |------|------
The index of BSS | The index of EV | The arrival time | The operating time | The waiting time | The index of SS | The departure time | The index of charger | The start charging time | The finish charging time | State of Charge | State of Health | load|
