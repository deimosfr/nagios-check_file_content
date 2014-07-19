nagios-check_file_content
=========================

Nagios file parser check

Usage
-----
```
Usage : check_file_content.pl -f file -i include -e exclude -n lines_number [-h]

Options :
 -f
	Full path to file to analyze
 -n
	Number of lines to find (default is 1)
 -i
	Include pattern (can add multiple include)
 -e
	Exclude pattern (can add multiple include)
 -h, --help
	Print this help screen

Example : check_file_content.pl -f /etc/passwd -i 0 -e root -n 5
```