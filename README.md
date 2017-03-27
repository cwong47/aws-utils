# aws-utils
Collections of utlities and tools designed to interact with aws-cli to simplify daily life! ;)

# Motivation
Sick and tired of clicking around AWS console! :P

# Utilities
1. **dnsgrep**
  * Searches thru AWS route53 DNS entries and display them in pretty formats ;)
2. **ec2lookup**
  * Searches thru AWS EC2 entries and display specific fields in pretty CSV formats which can then be parsed ;)
3. **elblookup**
  * Gets ELB health status and info.

# Setup
Copy the scripts to either `$HOME/bin` or `/usr/local/bin`, or add this repo to your `$PATH`.

I have something similar in my `.bash_profile`:
```
for p in /path/to/aws-utils/*
do
    [ -f ${p}/README.md ] && export PATH=$PATH:$p
done
```

# Contributors
Calvin Wong

# License
The utilities in this repo are distributed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0),
see LICENSE and NOTICE for more information.

# Repo Location
[https://gitlab.com/cwong47/aws-utils](https://gitlab.com/cwong47/aws-utils.git)
