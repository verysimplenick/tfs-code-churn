tfs-code-churn
==============
Counts the number of code commits for every .cs file in a TFS repository. Being a lowly developer in an organization that would surely never grant me the access required to generate and view the actual code churn reports, I turned to the internet for alternatives. The original code comes from [http://mark-dot-net.blogspot.com/2014/03/how-to-calculate-code-churn-using-tfs.html]. It needed minor modification to work with TFS 2010 and I wrapped it in a console application to write the contents to csv. It is not as telling as a full code churn report, but it at least can give some indication of likely candidates for high churn files.