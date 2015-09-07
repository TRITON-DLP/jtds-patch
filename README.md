# jtds-patch

### What is that project?
After upgrading to Java 8 we started to experience an issue with failures connection using SSL. A quick search in the internet shows that we are not the only ones: [http://sourceforge.net/p/jtds/bugs/725/]. 

Apparently the ticket above contains a patch for the issue as well ([http://sourceforge.net/p/jtds/bugs/725/#7b2b]) but no official release as of yet. In order to (a) be able to continue using jTDS with JRE 1.8 and (b) comply with the LGPL license we have created this project and made iy publicly available. 

### What is included?
* jTDS 1.3.1 as baseline
* The patch from the link above is applied
* 

So far this seems to be behaving well for us.
