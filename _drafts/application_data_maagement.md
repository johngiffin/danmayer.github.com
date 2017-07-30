I have been developing application code and working with teams of developers for over a decade. Application developers often don't treat data with the respect it deserves and it can come back to bite you in various forms.

* Data Refactoring
  * massive schema changes required 
* Data Integrity Failures
  * data duplication sync failures (same column multiple tables / DBs)
* Deprecated Tables and Columns galore

---

ways to improve

* [Data Change Management Process](https://www.mayerdan.com/programming/2016/11/21/managing-rails-migrations)
   * Information Architecture Redesign Flow 

* data unused tables
* unused columns *2
* move DB stuff to a gem (table and columns)  
* gemify the information architecture change approach