# operating-system-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [Operating-System Homework 1 Solved](https://www.ankitcodinghub.com/product/operating-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110239&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Operating-System Homework 1  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Outline:

1 Requirement (作業要求)

1.1 run built-in command

1.2 run single process command

1.3 run two-process pipelines

1.4 handle input and output redirection

1.5 execute commands in the background

1.6 run multi-pipelines

2 Built-in command requirement (1.1 的要求細節)

2.1 help/cd/echo/exit

2.2 record/replay

2.3 mypid

4 Grading (評分規則)

5 Precautions/Reference (注意事項/參考連結)

1.0 hello-message and prompt symbol (e.g., &gt;&gt;&gt; $ )

You can customize your hello-message when your shell starts running. The messages will not affect your score.

You must print prompt symbol.

1.1 run built-in command concept flow-chart: ↓

Please refer to 2 Built-in command requirement for detail implementation requirements

1.2 run single process command

If user input a line with only “space“ or “ ” characters, you should do nothing, and print another prompt symbol.

1.3 run two-process pipelines

1.4 handle input and output redirection

1.5 execute commands in the background

The parent-process (which runs the shell) should print the pid of the child-process (that runs the command in the background).

1.6 run multi-pipelines

With all the functionalities mentioned before, your shell should run the command smoothly.

When run multi-pipelines in the background, the original shell process should print the process’ pid of the right most command.

(For example, in the screenshot below, you will print the pid of the process that runs “grep” command.)

( 將 multi-pipelines 放到背景執行時, 原 process 要輸出的 pid 為: 執行最右側的指令的 process 的 pid )

last – 16

NAME record – show thecommands

SYNOPSIS record

including “ record” itself

DESCRIPTION Your shell will always record the last-16 commands that user used in the shell. When user type the “record” command, the shell will print the last-16 commands to stdout, .

The biggest number indicate the latest command being used (i.e., “record” itself).

If the command is not a legal command (e.g., “recorf” in p.17), that command will still be recorded. The only exception is the “replay” command, which itself will not be recorded.

See next page for example.

NAME replay – re-execute the command that is listed in record

SYNOPSIS replay [number] (1 &lt;= number &lt;= 16)

DESCRIPTION User should use the “replay” command with a number.

If the number is in legal range, the shell should re-execute the command according to the number listed in the “record” command.

If “replay” is used with wrong argument (not a legal number), your shell should output an error message “replay: wrong args”, and should not execute any command, neither be recorded.

IMPORTANT: The “replay” command itself will not be recorded in the shell. Instead, the command that are actually “be replayed” are recorded in the shell.

See next page for example.

NAME mypid – show the related pids about the process

SYNOPSIS mypid [-i|-p|-c] [number] (number indicate a process’ pid)

DESCRIPTION Depend on the flag used with the command, mypid will list the related process’ pid(s).

-i: print process’ pid, which execute “mypid”. (ignore [number]) -p: print process’ parent’s pid (i.e., who has child [number])

-c: print process’ child’s pid (i.e., whose parent is [number])

You must implement this command through parsing information in the /proc directory. (except for implementing the “-i” option).

See next two pages for examples and hints.

3 Input format

1. Only 4 special operators: |, &gt;, &lt; and &amp; .

2. All the cmds, args, operators will be separated by space char.

• 指令(cmd), 引數(arg) , 特殊符號(operators) 都會用空白符號隔開

3. Input/ redirection (&lt;) only show up after first command.

• Input redirection 的檔名一定會接在 &lt; 後面，且如果有，一定會緊接在第一個指令後面

4. Output redirection (&gt;) only show up after last command.

• Output redirection 的檔名一定會接在 &gt; 後面，且如果有，一定會緊接在最後一個指令後面

5. Background-execution operator (&amp;) will only show up at last.

• &amp; 如果有，一定會出現在最後面

格式範例1 範例2 範例3

$ cmd args &lt; infile | cmd args | cmd args &gt; outfile &amp;

$ cat &lt; t1.txt &gt; t2.txt &amp;

$ record | head –c 32 &gt; t2.txt &amp;

$ cat &lt; t1.txt | head -5 | tail -3 | grep pid &gt; t2.txt &amp;

4 Grading

• 助教會針對每一個要求 (1.1~2.3) 做測試，並詢問你問題。

• 你必須要能流暢的解釋你如何實做你的 shell 與如何完成這些功能要求。

• If you cannot explain smoothly, you will not get scored.

• 如果你無法解釋你是怎麼寫出這些功能的，你就不會拿到分數

Github classroom:

Click here to start your assignment.

• You should implement HW1 with C language.

• You will get two files: makefile, my_shell.c from the hw1 github classroom.

• Make sure your main() function is written in the file my_shell.c.

• You can modify makefile as you want. E.g., add other files and compile them with your my_shell.c using your modified makefile.

• Make sure your makefile can compile your codes and create the executable smoothly . The executable name should be: my_shell.

• Make sure your codes can be compiled and run in the DEMO environment introduced in the hw0 slide.

System-calls/library-calls that might help: getline / strtok_r / strsep / strtol fork / execvp / waitpid / exit pipe / dup2 open / close / read / write opendir / readdir / closedir chdir/ getcwd

Other reference link:

• Tutorial – Write a Shell in C

• GNU Libc Manual Page – Implementing a Shell

• /proc filesystem

• GNU Makefile Documentation
