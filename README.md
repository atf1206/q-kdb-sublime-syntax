# q-kdb-syntax
q/kdb syntax parsing/highlighting

* Includes syntax parsing/highlighting for q/kdb 3.x, 2.x, k, and q output 
* can be used with text editors (Sublime, others), IDEs, github, etc.

## Details
This version stays largely faithful to the current [sublime-q](https://github.com/komsit37/sublime-q) syntax highlighting by [kimtang](https://github.com/kimtang/sublime-q), with updates and fixes:

* Parses numbers better, including reals;
* Supports all nulls and infinities;
* Parses symbols better;
* Properly handles escape characters in strings (including unicode);
* Correctly interprets comments and block comments;
* Contains an updated list of reserved words;
* Still uses the reversed function-definition/function-argument highlighting that you know and love;
* Does **not** highlight all your parentheses;
* Highlights view/global assign ('::') in the same way as assign (':');
* Speaking of assignment, now highlights compound assignments (such as '+:' and ',:'). Also, my personal favorite, dictionary assignments (e.g. 'dict\[`key\]:value');
* Not only highlights all date and time varieties, but even flags them as the correct type under the hood!! (For example, in Sublime you can use ctrl+shift+p to view the context of your cursor --
" handy for qbies!);
* Highlights IO functions ('0:' and '1:');
* (Slightly) improved k language and q-output highlighting;
* Also (slightly) improved namespace and built-in namespace highlighting;
* And more!
 
