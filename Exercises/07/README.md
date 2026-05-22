Drip-feed scan path
===================
The goal of this exercise is to create a scan path piece by piece. In order to
do this, you will need to modify the `input.info` file and create a new scan path file
`drip_feed_scan_path.txt`. Use the scan path in `drip_feed_scan_path_1.txt` to
help you create the initial scan path. Then launch the simulation and use the
data in `drip_feed_scan_path_2.txt` to finish the scan path. Do not append to
the scan path in `drip_feed_scan_path.txt`. Write is not an atomic operation.
Instead create a temporary file and them overwrite (using `mv`) 
`drip_feed_scan_path.txt`. You can run the exercise using `./adamantine -i input.info`. 
The solution of the exercises is given in `solution.info` and `solution_scan_path.txt`.
Please refer to the documentation in the
[time_stepping](https://adamantine-sim.github.io/adamantine/doc/input_file.html#time_stepping-required) 
and [event format](https://adamantine-sim.github.io/adamantine/doc/scan_path.html#event-format) sections.

Five-axis
=========
Modify the scan path to print vertically.
