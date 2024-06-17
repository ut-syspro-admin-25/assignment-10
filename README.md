# assignment-10
Virtual memory and paging.

Information
Course: system programming (Mon, 3rd & 4th)
Classroom: Faculty of Science Bldg.7 Room#214
Main Instructor: Takahiro Shinagawa
Teaching Assistant: Momoko Shiraishi, Ryo Nakashima, Seiga Ueno, Sungying Chiang, Keisuke Iida
Assignment
Slide: here(ECCS email required)
Date due: 2024/07/8 (tentative: check here for the latest deadline.)
How to Transfer
$ bash assignment-9-xxx/scripts/transfer.sh assignment-9-xxx assignment-10-xxx
How to Build
$ make docker-build # Only the first time

$ make docker-make
cf: https://github.com/pflab-ut/utokyo_syspro_baremetal_2023

How to Run
$ make qemu
How to Debug
$ git am --3way </path/to/patch_file> # Only the first time

$ make qemu-gdb &
$ gdb -iex 'add-auto-load-safe-path .'
Notes
Make sure that codes can be successfully built by TA.
Check the ✅ after the final push.
Submission might be rejected due to deficient files.
