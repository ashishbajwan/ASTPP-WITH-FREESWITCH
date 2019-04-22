# ASTPP-WITH-FREESWITCH
Requirements :

              1) CENTOS 7 WITH FRESH INSTALLATION
              2) SCRIPT ./INSTALL

STEPS :

      1) Download the script install.sh from here 
                                or 
           wget --no-check-certificate http://bit.do/astpp36-installation -O install.sh
      
      2) chmod +x install.sh
      
      3) ./install.sh
      
      4)  cd /var/lib/astpp
      
      5) gedit astpp-config.conf
      
      6) Change base_url in astpp-config.conf :
                                                       base_url=http://localhost:8089/
      
      7) Open browser and paste this url in addressbar
      
                                                        http://localhost:8089/
      8) Done
