# ruby-windows-problems
Common run-ins with Ruby/Rails using Windows 10

* **SSL Certification Error**  
  When trying to install/update a Ruby gem via the command line this error is received:  
  ```
  ERROR:  Could not find a valid gem 'rubygems-update' (= 2.6.6), here is why:  
  Unable to download data from https://rubygems.org/ - 
  SSL_connect returned=1 errno=0 state=SSLv3 read server certificate B: 
  certificate verify failed (https://api.rubygems.org/specs.4.8.gz)
  ```  
  [Solution](https://github.com/JessBohn/ruby-windows-problems/blob/master/ssl-certificate-error.txt, "SSL Certification Error Solution")
