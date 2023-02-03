#### This project intends to diversify my knowledge o Load Balancing Techniques using NGINX webserver, a consolidtaion on the existing knowledge of the use of Apache for Load Balancing
#### Project10 of Banjo Babade at darey.io 
![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_224530.png)
setting 443(HTTPS) protocol  inbound security rules on the instace to bounce MIMT attacks (Man In the Middle Attacks)
![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_224551.png)

installing nginx
![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_224816.png)

editing nginx.conf file sudo vi /etc/nginx/nginx.conf
![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_231357.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_231421.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_235219.png)

installing and configuring certbot on nginx 
![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_235443.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230129_235731.png)

#### At this point I used namecheap.com to register babade.online thus the congiguration steps was found on https://aws.plainenglish.io/how-to-point-namecheap-domain-to-aws-ec2-instance-8b0544cc2c88 

Creating elasttic IP
![Alt text](Screenshot_20230203_035421.png)
![Alt text](Screenshot_20230203_035443.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_123920.png)
using Route 53 service on aws

https://medium.com/progress-on-ios-development/connecting-an-ec2-instance-with-a-godaddy-domain-e74ff190c233 this article is frp Godaddy.com user

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_124058.png)

Name servers generated successfully from Route 53 using the Elastic IP 
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_124527.png)

Using the Elastic IP for configuration on Rout 53

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_125223.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_125802.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_130027.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_130221.png)

copied the generated name servers to my DNSserver address in Namecheap
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_130239.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_131303.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_133852.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_134149.png)


Certbot configured on babade.online
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_135141.png)

Certbot configured on babade.online
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_135333.png)

Certbot configured on babade.online successfully
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_145101.png)

certificate screenshot
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_145315.png)

![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_145540.png)

crontab configuration
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_145958.png)

Load balancing and HTTPS(443 protocol)  achieved successfully
![Alt text](IMG-SCREENSHOTS/Screenshot_20230131_151919.png)

Devop Journey , a very Interesting one Indeed...................

