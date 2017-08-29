# awk-tricks

Keep one instance of all the duplicate lines in a file.

`awk '!seen[$0]++' file`

Parse a csv file.

`awk -F "\"*,\"*" '{print $COL}' file`

Sum a particular column of a file.

`awk '{sum+=$COL} END {print sum}' file`
