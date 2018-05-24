# Webkit PoC from 5.50 to 5.55 made by Ciss84, added work by ShadixAced and iSn0we.
# NOTE : Al-Azif Exploit Host now works on 5.53-01 and 5.55 as I've tested it. (17/05/18)
# Double Note : Al-Azif Exploit Host is often detected as a virus for antiviruses. It's a false positive. To use this program, exclude it using your Antivirus parameters or disable it for the time you need.

# Changes made :

add ping

add loader

add all syscall

add var instancespr 2048

add all gadgets

add var thread2

add kchain

add var scratch

add var test = kernel_rop_run(fd1, scratch);

update in rop gadgets 10/05/2018

update readme and index.html

update in rop gadgets 11/05/2018

fix stability and add alasif server

add new code in rops and expl

update gadget and malloc code and stackPointer and stkebase and ping

update server for 5.55

added ps4 MiraFW_Orbis payloads 501/505
