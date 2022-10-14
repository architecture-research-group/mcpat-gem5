# mcpat-gem5
git repo for porting gem5 output to mcpat. The code is based on this repo [https://github.com/TAKAKEYA/gem5tomcpat.git](https://github.com/TAKAKEYA/gem5tomcpat.git) 

```
# Where to store the "mcpat-out-0.xml" file 
mkdir mcpat_output

# Works with python 2.7
python pars.py PATH_TO/m5out/stats.txt PATH_TO/m5out/config.json template-o3.xml -o mcpat_output
```
