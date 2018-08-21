# linux-commands . 
which . 
ls -alogF . 
whoami . 
export ASPNETCORE_URL= . 
export ASPNETCORE_URL="http://+:3222" . 
echo $ASPNETCORE_URL . 
/var/mywebsite . 
cp -a /var/mywebsite . 
systemctl . 
which systemctl . 
systemctl status nginx . 
systemctl start nginx . 
systemctl stop nginx . 
systemctl enable nginx . 
systemctl restart nginx . 
sudo systemctl daemon reload . 
/lib/systemd/system/nginx.service    
/etc/nginx/sites-available . 
nginx -s reload . 
     
#simple starter config . 
[Unit] . 
#80 char maximum . 
Description=Sample .Net Web App . 

[Service] . 
Type=simple . 
WorkingDirectory=/var/mywebsite . 
ExecStart=/usr/bin/dotnet /var/www/webapp/sampleapp.dll . 
User=web . 
  
  
  
