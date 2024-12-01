
 _____ _                      _           _ _            
|_   _| |                    | |         | (_)           
  | | | |__   ___  ___  _ __ | |__  _   _| |_ _ __   ___ 
  | | | '_ \ / _ \/ _ \| '_ \| '_ \| | | | | | '_ \ / _ \
  | | | | | |  __/ (_) | |_) | | | | |_| | | | | | |  __/
  \_/ |_| |_|\___|\___/| .__/|_| |_|\__, |_|_|_| |_|\___|
                       | |           __/ |               
                       |_|          |___/                

TruLone's last malware.

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=

Theophyline is a GDI malware consisting of 8 payloads & 7 sounds. 
Both GDI and sound payloads are randomized thanks to AG5516 helping me with ExitThread.
It is at the same time very destructive, as it can overwrite your disks
without a chance of recovery and delete system files. It, when executed,
starts spamming messages, device inputs, text labels renaming, ghost window showing and
system cursor changing.

kthx bye <3