# VMware-Workstation-Ubuntu
how to install a VMware Workstation for your Ubuntu
<pre>
sudo apt-get update
sudo apt-get upgrade
wget https://download3.vmware.com/software/wkst/file/VMware-Workstation-Full-11.0.0-2305329.x86_64.bundle
chmod a+x VMware-Workstation-Full-11.0.0-2305329.x86_64.bundle
sudo ./VMware-Workstation-Full-11.0.0-2305329.x86_64.bundle
</pre>
<br />notice:this software will use your port:443  and if you have install xampp .It use the port:443 too. This is a big problem.Your apache will not start correct. so change the port to 4433.
