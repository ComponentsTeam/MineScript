Prerequisites
=============

* Oracle Java Runtime Environment (JRE) 7
* bash, located in /usr/bin
* Working knowledge of SSH
* Working knowledge of bash


Installing Oracle JRE 7
=======================

Most Linux distributions package variations of OpenJDK.  While OpenJDK is adequate for most Java applications, it is not supported by Mojang or MineScript, and may not provide the same performance as the Oracle JRE.  Oracle has requested that its JRE/JDK not be packaged by Linux distributions, instead requiring end users to visit its website.

The JDK is aimed at developers, and provides the tools to develop Java applications from source, as well as to run compiled Java applications.  The JRE can only run compiled Java applications.  The JDK includes the JRE.  Only the JRE is required to run a Minecraft server, and is advisable for most server installations.  Forge mod and Bukkit plugin development require the JDK, but this should not take place on a deployed Minecraft server under most circumstances.  Installing the JRE will allow you to upgrade to the JDK later.  If you are confused as to whether to install the JRE or the JDK, you should install the JRE.

1. Download JRE 7 or JDK 7 archive from the [Oracle website](http://www.oracle.com/technetwork/java/javase/downloads/index.html).  The download is designed to prevent use with curl/wget; advanced users can circumvent this by copying the cookies from their browser to the server.  Normal users should see the section about [Getting Files onto the Server](#Getting_Files_onto_the_Server).  Most servers will require the "Linux x64" version.  If your operating system or server is not 64-bit, you should download "Linux x86" instead, but you will be limited to 4 GB of RAM.  If you had the option at some point to choose between a 32-bit (x86, i386, i686) OS and a 64-bit (x64, x86\_64, amd64, i686\_64) OS, go back now and re-image your server with a 64-bit version of Linux.
2. Extract the archive using the command `tar -xf archive.gz`, replacing "archive.gz" with the name of the file that you downloaded in Step 1.
3. You should have a folder 


<a name="Getting_Files_onto_the_Server"></a>
Getting Files onto the Server
============================

Getting files onto your Linux server is easier than you might think.  If you have SSH access to your server, you likely already have everything that you need.  You do not need to install an FTP server.

FTP is insecure and is, to some extent, considered obsolete in the Linux world.  SFTP-over-SSH is the popular replacement.  To the end user, SFTP appears to work just like FTP.  Behind the scenes, SFTP is secure, and can utilize existing SSH services and credentials.

Popular SFTP clients include WinSCP for Windows, Nautilus for GNOME (typically on Linux), and Cyberduck for Mac OS X.  Advanced Linux users may prefer the command-line utility "scp" for this purpose.


License
=======

Copyright (c) 2012 Paul Buonopane.  All rights reserved.  "Components", "MineScript", and "Zenexer" are trademarks of Paul Buonopane.

This product and its source code are made available for both commercial and non-commercial use.  You may use the product and its source code under the following conditions:

* This license remains in place.
* Any README, README.markdown, and similar documents are included with any portion of the source code.
* Any README, README.markdown, and similar documents are included with any portion of the compiled product.
* Any modifications become the property of the above stated copyright holder.  You hold no rights to modifications.
* You will immediately destroy all copyright-protected works upon request of the above stated copyright holder.

PROVIDED THE AFFOREMENTIONED CONDITIONS ARE MET, you are entitled to the following, unless otherwise revoked by the above stated copyright holder:

* You may use the above stated trademark(s) to endorse your commercial and/or non-commercial products.
* You may modify the copyright-protected work(s).
* You may redistribute the copyright-protected work(s), in part or in whole.

