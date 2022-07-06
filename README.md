# reverseOrRotate
The input is a string str of digits. Cut the string into chunks (a chunk here is a substring of the initial string) of size sz (ignore the last chunk if its size is less than sz).  If a chunk represents an integer such as the sum of the cubes of its digits is divisible by 2, reverse that chunk; otherwise rotate it to the left by one position. Put together these modified chunks and return the result as a string.  If  sz is &lt;= 0 or if str is empty return "" sz is greater (>) than the length of str it is impossible to take a chunk of size sz hence return "". Examples: revrot("123456987654", 6) --> "234561876549" revrot("123456987653", 6) --> "234561356789" revrot("66443875", 4) --> "44668753" revrot("66443875", 8) --> "64438756" revrot("664438769", 8) --> "67834466" revrot("123456779", 8) --> "23456771" revrot("", 8) --> "" revrot("123456779", 0) --> ""  revrot("563000655734469485", 4) --> "0365065073456944" Example of a string rotated to the left by one position: s = "123456" gives "234561".


== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project.  We have an
[open {bug ticket, mailing list thread, etc.} ](INSERT_LINK) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the
[Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) to understand
some of the reasons why GitHub is not a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
[check this resource](INSERT_LINK) for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)
