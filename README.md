# aws-utils
Collections of utlities and tools designed to interact with aws-cli to simplify daily life! ;)

# Motivation
Sick and tired of clicking around AWS console! :P

# Utilities
1. **dnsgrep**
  * Searches thru AWS route53 DNS entries and display them in pretty formats ;)
2. **ec2lookup**
  * Searches thru AWS EC2 entries and display specific fields in pretty CSV formats which can then be parsed ;)

# Setup
Copy the scripts to either `$HOME/bin` or `/usr/local/bin`, or add this repo to your `$PATH`.

I have something similar in my `.bash_profile`:
```
for _path_i in /path/to/aws-utils/*
do
    [ -f ${_path_i}/README.md ] && export PATH=$PATH:$_path_i
done
```

# Contributors
Calvin Wong

# License
DNS Grep (dnsgrep) is distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0),
see LICENSE and NOTICE for more information.

# Repo Location
[https://gitlab.com/cwong47/aws-utils](https://gitlab.com/cwong47/aws-utils.git)
