Warning Cascading Data

Tools:
We used GumTree, SCALe, and Hydrogen to analysis the warnings generated by static analysis tool.

GumTree: https://github.com/GumTreeDiff/gumtree

SCALe: https://github.com/cmu-sei/SCALe/tree/scaife-scale

Hydrogen: https://github.com/iowastateuniversity-programanalysis/hydrogen

The real-world warnings that Static analysis tool directly generated is save at [Warning_Cascading](https://github.com/WarningCas/WarningCascading_Data/tree/master/real-word-set-result).

The we have the real-word result saved in the [real-world-set-result](https://github.com/WarningCas/WarningCascading_Data/tree/master/warnings_sqlite).

The &lt;benchmark&gt;.&lt;verison1&gt;-match.txt represent Hydrogen result that detected as 'same bug' (match) where &lt;benchmark&gt;.&lt;version1&gt;-unmatch.txt represent 'bug fix' (unmatch) for Hydrogen.

Notice the Hydrogen result is after the preprocessing step.

we have Gumtree's result as &lt;verision1&gt;.csv as 'same bug'  (match)

we have SCALe's result as &lt;benchmark&gt;-&lt;verison1&gt;.txt with 'same bug' (match)

The table we used to record the running result of each tool is Experiments_result.xlsx


