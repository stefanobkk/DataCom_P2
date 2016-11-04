**Project2: puncher_bag**
---------------------------

Partner: Nook, u5580025


The filename 'punch' is the most up-to-date version

To run 
./punch -n <numRequsts> -c <macConcurrent> <url>
===================



Remark:<br/>
1. just use max concurrent of 200 and numrequest of 100000 to get the maximum performance<br/>
>./punch -n <numRequests> -c <maxConcurrent> <url><br/>


Features:<br/>
1. This use asyncore library, be sure to import it correctly<br/>
2. In testing we managed to get around 40,000 request per second. 
3. We had to used a method of re-connection to prevent the program from stopping as we had some problems 
   with the socket disconnecting. 
