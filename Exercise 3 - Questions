Question 3.1
What different severities does Nessus report for vulnerabilities? 
 - Nessus reports on five severity levels: informational, low, medium, high, and critical 
Question 3.2
Given just the uncredentialed scan, what is the most severe vulnerability according to Nessus? Why has Nessus given this vulnerability this rating? 
  - From the uncredentialed scan, one of the most severe vulnerabilities reported was "Canonical Ubuntu Linux EoL." The reason for its high rating is that it lacks support, which 
implies that there are no new security patches for the product, thus making it more prone to vulnerabilities.
Question 3.3
Now, according to the credentialed scan results, what is the most severe vulnerability according to Nessus? Why does this vulnerability have a higher VPR severity score than the previously identified vulnerability? 
 - From the credentialed scan, the most severe vulnerability according to VPR is "Bash Remote Code Execution (Shellshock)." It has a VPR score of 9.6 because it is a serious vulnerability that allows attackers to remotely execute arbitrary commands.
Its high VPR also reflects the real-world threat of exploitation, making it a higher priority than other vulnerabilities. 

Question 3.4
Using what plugin(s) can we validate that the credentialed scan was successful in logging into the target system? 
 - The "Target Credential Status by Authentication Method" plugin confirms that Nessus successfully logged into the target system. The output shows that Nessus 
authenticated using SSH on port 22 with the username "msfadmin" and password authentication.

Question 3.5
The credentialed scan was successful in logging into the target Metasploitable system, but had some issues performing everything it was trying to accomplish. What happened here? 
 - Nessus was able to execute credentialed checks because it was possible to log in to the remote host using the provided credentials; however 
the credentials were not sufficiently privileged to complete all requested checks.
