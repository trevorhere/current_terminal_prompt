# Current Terminal Prompt
bash code for my current terminal promp:

![current terminal prompt](https://i.imgur.com/rIM90zT.png "")

``` export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[92m\] \[\033[0;36m\]\w\[\033[m\]\[\033[0;92m\][\$(git branch 2>/dev/null |grep '^*' | colrm 1 2)]\033[m\]💯: "   ```
