By Referring to C-based Lab videos and RISC-V-based lab videos

Snapshots of the compiled C code and RISC-V

Step 1: check whether the leafpad is installed in ur machine by using the commands leafpad sum1ton.c& (sum1ton.c is the file name) If the leafpad editor is opened without any errors then type the C code. **If the leafpad is not installed in ur machine then install by using the following command

sudo snap install leafpad**

**Step 2: Writing the C code in the leafpad editor using the following command

leafpad sum1ton.c&

![21](https://github.com/Chetanmaligi/maligichetan/assets/154491089/1b0ac1a6-1248-4db1-ba3d-9323fd2de321)
Step 3: After writing the C code save the editor by Ctrl+s


![22](https://github.com/Chetanmaligi/maligichetan/assets/154491089/6a0b33cb-c0a2-474a-b874-bfe890707d04)

Step 4: Check for the errors by using the following command(compilation step)

gcc sum1ton.c

Step 5: Check the output by using the command

./a.out
![23](https://github.com/Chetanmaligi/maligichetan/assets/154491089/d27ee50c-f4ac-4e1c-9344-0a5a070f2c94)
The results will be displayed as

Sum of numbers from 1 to 50 is 12

***RISCV Compilation and Execution

Step 1: View the C Code in the editor window using the following command

cat sum1ton.c
![24](https://github.com/Chetanmaligi/maligichetan/assets/154491089/171c4ae9-25ae-4b63-8a0f-830d0af30134)
Step 2: Compile the code in riscv using the following command

riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c


![24](https://github.com/Chetanmaligi/maligichetan/assets/154491089/11244683-9e1d-4f2a-a1e4-c706ad8f2c83)

Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.

use the command

ls -ltr sum1ton.c
![24](https://github.com/Chetanmaligi/maligichetan/assets/154491089/57905490-b3ae-43fa-96ef-379a47260e3b)

![31](https://github.com/Chetanmaligi/maligichetan/assets/154491089/23ba249e-37e5-419e-9ada-8db727aa776e)
Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution
![32](https://github.com/Chetanmaligi/maligichetan/assets/154491089/eeb56789-5d47-4355-9146-91ffdf567b8c)
![33](https://github.com/Chetanmaligi/maligichetan/assets/154491089/383f5ef7-c3a9-4472-aaa7-8c5debf0be27)
Step 4:

riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c

![34](https://github.com/Chetanmaligi/maligichetan/assets/154491089/f047c897-0e73-4c00-b910-072cb31f84d1)


![35](https://github.com/Chetanmaligi/maligichetan/assets/154491089/5378ad6b-90ae-456e-9ec9-32e7dac2ab42)






