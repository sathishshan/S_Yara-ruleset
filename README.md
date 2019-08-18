# S_Yara-ruleset ~ Significance_Yara-ruleset

S_yara-ruleset is based on Web Malwares, rules are written in more efficient by using generic and specific malware types.

### Minimal Yara Usage:
 ```
yara [OPTIONS] RULES_FILE TARGET

 -r --recursive  
     Recursively search for directories.

 -s --print-strings  
     Print matching strings.

 -f --fast-scan  
     Fast matching mode.

 -w --no-warnings  
     Disable warnings.

 -v --version  
 	 Show version information.

 -h --help  
     Show help.

```
- RULES_FILE can be passed directly in source code form, or can be previously compiled with the yarac tool. You may prefer to use your rules in compiled form if you are going to invoke YARA multiple times with the same rules. This way you’ll save time, because for YARA it is faster to load compiled rules than compiling the same rules over and over again.

### Minimal Yarac Usage:
```
yarac - compile rules to yara
        yarac [OPTION]... [RULE_FILE]... OUTPUT_FILE
        
 -w disable warnings.

 -v show version information.
```
[Yara Full Docmentation.](https://yara.readthedocs.io/en/v3.8.1/){:target="_blank"}  
[Writing Yara rules](https://yara.readthedocs.io/en/v3.8.1/writingrules.html){:target="_blank"}  

