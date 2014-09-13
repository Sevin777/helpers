helpers
=======

debugging and logging helper methods

##jsParseBenchmark.html
- Used to test how long it takes to PARSE a javscript library (when its loaded from cache)
- Instructions are in the comments of the file (open and modify it)
- This is something that is typically difficult to benchmark, but it is critical to load time
- If you want to see the real impact of a large library, try loading jQuery + Kendo UI (Kendo UI is takes forever to parse!)
- This file is really messy as I made it very quickly and dont care to clean it up
