# thingamabill
A retro translation tool for the 21st century


### Features ---> Planned

Hex editing but translation focused

* .tbl support
    * conditional tbl; only apply tbl between certain byte sequences
* relative search
* cdl support
* **scripted easy-editors** - using collect up byte sequences based on user function into a list of form controls for quick editing
* scripted display - write a function to add a data display type to the info pane (e.g. user function that interprets 2 bytes as fixed point)
* scripted search - user function callback to process byte sequences as we go
* pointer finder - auto-find probable pointers like 2-byte sequences that only increase
* markov search - use a language transition table (starting with Japanese) to find probable text sequences
* entropy-aware search - mark probable areas based on entropy calculation e.g. Shannon Entropy or other metrics
* code-aware search - analyze probable code vs data (even if CDL hasn't marked) to provide search inside data most likely areas
