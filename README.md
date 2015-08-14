# Conmon

Internet status monitoring tool. Conmon monitors your connection for given time and interval. It logs the result in current working folder. It also can monitor if dns query fails, but otherwise connection works fine.

##--Usage--

python conmon.py -t TIME -i INTERVAL [-d]

-t Monitoring time

-i Interval between up/down testing

-d Test if only dns fails(optional)

Todo: Finish Windows compatibility and multiprocessing.
