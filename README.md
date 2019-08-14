# q-kdb-syntax
q/kdb syntax parsing/highlighting

* Includes syntax parsing/highlighting for q/kdb 3.x, 2.x, k, and q output 
* can be used with text editors (Sublime, others), IDEs, github, etc.

## Details
This version stays largely faithful to the current [sublime-q](https://github.com/komsit37/sublime-q) syntax highlighting by [kimtang](https://github.com/kimtang/sublime-q), with updates and fixes:

* Parses numbers better, including reals;
* Supports all nulls and infinities;
* Parses symbols better;
* Parses file handles;
* Properly handles escape characters in strings, including unicode;
* Correctly interprets comments and block comments;
* Updates the list of reserved words;
* Still uses the reversed function-definition/function-argument highlighting that you know and love;
* Does **not** highlight all your parentheses;
* Highlights view/global assign ('::') like assign (':');
* Speaking of assignment, now highlights compound assignments (such as '+:' and ',:') and dictionary assignments ('dict\[`key\]:value');
* Not only highlights all date and time varieties, but also flags them as contexts under the hood (for example, in Sublime you can use ctrl+shift+p to view the context of your cursor -- handy for qbies);
* Highlights IO functions ('0:' '1:' and '2:');
* (Slightly) improves k language and q-output highlighting;
* Also (slightly) improves namespace and built-in namespace highlighting;
* And more!
