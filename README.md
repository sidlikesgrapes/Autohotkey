# Autohotkey
This is a project to type in the most common used particles of code in java.
Copy below and paste it in a .ahk file

#NoEnv  ; Step 1- Download AutoHotKey application first from- https://www.autohotkey.com/download/ahk-install.exe
; #Warn  ; Step 2 - run this file with autohotkey, if it does not show any errors, it has started working.
SendMode Input  ; 
SetWorkingDir %A_ScriptDir%  ;  Below are Hotkeys which type their respective sentences. 

*f1::
Send, System.out.println("");
return

*f2::
Send, void main()
return

*f3::
Send, Scanner sc = new Scanner(System.in);
return

*f4::
Send, int x = sc.nextInt();
return


*f5::
Send, while() 
return

*f6::
Send, for() 
return

*f7::
Send, switch (x)
return

*f8::
Send, case 1:: break;
return
     
