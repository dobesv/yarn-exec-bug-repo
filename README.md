# temp-project

To reproduce the issue:

   yarn
   yarn runme &
   ps auxwww | grep runme
   kill xxx # replace with the FIRST pid
   
Notice whether the script is actually terminated.
