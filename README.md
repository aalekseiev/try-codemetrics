# try-codemetrics
Readme for different codemetrics tools

versioning control querying tool:
<pre>
prompt> maat -l maat_evo.log -c git -a summary
statistic,value
number-of-commits,88
number-of-entities,45
number-of-entities-changed,283
number-of-authors,2
</pre>

lines of code tool:
<pre>
prompt> cloc ./ --by-file --csv --quiet
language,filename,blank,comment,code
Clojure,./src/code_maat/analysis/logical_coupling.clj,23,14,145
Clojure,./test/code_maat/end_to_end/scenario_tests.clj,23,19,117
Clojure,./src/code_maat/analysis/churn.clj,14,11,99
Clojure,./src/code_maat/app/app.clj,13,6,94
Clojure,./test/code_maat/analysis/logical_coupling_test.clj,15,5,89
...
</pre>
