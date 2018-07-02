# How to replace shiny server starter-page with own website

#### where to find the page

- standart shiny server config in Ubuntu 16.04 places the starter-page in directory **/srv/shiny-server**

 If changes to default shiny server configs were made, you find them in the file: **/etc/shiny-server/shiny-server.conf** 
 
 #### how to replace it
 
 - to do following instructions, you need **root** access
 - create backup of original shiny server page: 
 >- cd /srv/shiny-server
 >- sudo mkdir shiny_webpageBKUP
 >- sudo mv * shiny_webpageBKUP
 
 - get repo of your desired webpage (this repo for example) to your home directory and  move page to /srv/shiny-server
  >- cd; git clone https://github.com/MoserLab/404_page.git; cd 404_page
  >- sudo cp -r * /srv/shiny-server
      

 
## **404 demo page**

### https://moserlab.github.io
 


