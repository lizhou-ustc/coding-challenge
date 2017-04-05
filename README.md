## Run the code
--
This solution is using Python version 3.6.0. The required packages are numpy, Bottleneck and arrow.
All the require packages and versions are listed in requirements.txt. Uncomment the line '#pip....' in run.sh to install the packages.

I added one addition feature to detect the patter of a DoS attack. If an IP visited more than 10 times in 10 seconds,
this IP will be blocked for 5 minutes. In my code, I will record the blocked IPs in log_output/DoS.txt

