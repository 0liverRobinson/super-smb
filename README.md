# Super smb

![image](https://github.com/0liverRobinson/super-smb/assets/50546763/a0c6880d-1e60-436a-9a96-200aab92e8df)


# Description:

A linux based client for SMB servers built in C++.

<b>Disclaimer: </b><i>Due to the insecure nature of the smbv1 protocol, <b>use at your own risk</b>. I hold no liability in how you use this software.</i>

# Key Features:

Note: This <i>only works for SMBv1</i>. 

Supported Dialects include:
<ul>
  <li>An SMB Client supporting the following dialects: 
    <ul>
        <li>LAN MAN v1</li>
        <li>NT LM 0.12</li>
        <li>PCLAN1.0</li>
      </ul>
  </li>
</ul>


# Installation

Prerequisites:
<ul>
  <li>Linux based operating system (e.g. Kali, Ubuntu, Mint etc...)</li>
  <li>Clang 14.0.6</li>
</ul>

# Run

<pre>
  ./supersmb -i ip_addr -u username -p password -s share_name
</pre>

# Acknowledgements

This project uses the following open source libraries and open specifications:

- [Gtkmm](https://www.gtkmm.org/): C++ wrapper for GTK, a library for GUI.
- [Gtk](https://www.gtk.org): C Gui Library
- [MS-CIFS](https://winprotocoldoc.blob.core.windows.net/productionwindowsarchives/MS-CIFS/[MS-CIFS].pdf) The specification in which this project is based off.
