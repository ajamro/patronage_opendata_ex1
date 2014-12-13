patronage opendata exercise 1
=============================

This repository contains BLStream patronage challenge solution from the
OpenData track.

installation
------------

This program requires python 2.6 or later (works in python3) and have no extra dependencies.

You should be able to run it from the command line after installing only python
interpreter.

usage
-----

run from this command from the console:

	$> python csv2json.py --help

to get this help screen:

	usage: csv2json.py [-h] [csvfile] [jsonfile]

	BLStream patronage challenge solution

	positional arguments:
	  csvfile     defaults to stdin
	  jsonfile    defaults to stdout

	optional arguments:
	  -h, --help  show this help message and exit


results from the exercise can be obtained using following command:

	python3 csv2json.py CsvSampleOpenData\ Zadanie\ 1.csv result.txt
