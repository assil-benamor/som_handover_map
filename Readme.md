# som_handover  

## [<u>DSA][1]</u>  

### [Data collection preparation][2]  

* Python script to assign enumerators to sites using K-means clustering algorithm  
Input needed:   
  - Master list   
- Number of enumerators per district  

### [Data collection][3]  

* [Kobo tool checker][4]  
* Check the kobo relevant columns to make sure the skip logic is working properly  
* [<u>Quality checks][5]</u>  
  * A set of checks ( generic and specific ) to flag issues in the dataset. Output is a html page that can be shared with FOs/ AOs directly  
* [Real time monitoring][6]  
* [Backend][7]  
* Python script to update mysql tables with data collection summary ( how many times each site has been assessed )  
Automate execution of the script can be set using crontab [man7.org/linux/man-pages/man5/crontab.5.html][8]  

Useful links on how to install and set up mysql on a linux server:   
  - [digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04][9]  
- [digitalocean.com/community/tutorials/how-to-allow-remote-access-to-mysql][10]  
- [techexpert.tips/mysql/mysql-force-password-authentication/][11]  

* [Shiny][12]  
* Web app to be used by the enumerators to check if they can conduct an interview in a given site after introducing its p_code  
**The shiny app won’t work if the linux and mysql servers were not created and configured**  
  
  * [<u>Analysis][13]</u>  
  
  ### [<u>Analysis][14]</u>  
  
  ## [H2R][15]  
  
  ### [Aggregation][16]  
  
  * Make sure to update the files under [<u>input/dependencies_SL_NC][17]</u> after each tool update  

### [Analysis][18]  

* Results table generator for ki_data  

## JMCNA  

### [Analysis][19]  

* Analysis file to generate results tables, tableau input, weights calculation, PIN indicators  

### [PIN][20]  

* Excel files to compute the PIN figures for each cluster  

### [MSNI][21]  

* MSNI indicators coding and scores calculation  

[1]: https://github.com/lilos404/som_handover/tree/main/DSA  
[2]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection%20preparation  
[3]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection  
[4]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection/Kobo%20tool%20checker  
[5]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection/Quality%20checks  
[6]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection/Real%20time%20monitoring%20  
[7]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection/Real%20time%20monitoring%20/Backend  
[8]: https://man7.org/linux/man-pages/man5/crontab.5.html  
[9]: https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-18-04  
[10]: https://www.digitalocean.com/community/tutorials/how-to-allow-remote-access-to-mysql  
[11]: https://techexpert.tips/mysql/mysql-force-password-authentication/  
  [12]: https://github.com/lilos404/som_handover/tree/main/DSA/Data%20collection/Real%20time%20monitoring%20/Shiny  
[13]: https://github.com/lilos404/som_handover/tree/main/DSA/Analysis  
[14]: https://github.com/lilos404/som_handover/tree/main/DSA/Analysis  
[15]: https://github.com/lilos404/som_handover/tree/main/H2R/Aggregation  
[16]: https://github.com/lilos404/som_handover/tree/main/H2R/Aggregation  
[17]: https://github.com/lilos404/som_handover/tree/main/H2R/Aggregation/inputs/dependencies_SL_NC  
[18]: https://github.com/lilos404/som_handover/tree/main/H2R/Analysis  
[19]: https://github.com/lilos404/som_handover/tree/main/JMCNA/Analysis  
[20]: https://github.com/lilos404/som_handover/tree/main/JMCNA/PIN%20Files  
[21]: https://github.com/lilos404/som_handover/tree/main/JMCNA/MSNI  
