# Bootstrap-3  CRON Expressions generator:

msCron is a Jquery plug-in  which helps you to build cron expressions. msCron generated expressions are based on Quartz cron format. For your feedback send email to msbrother445@gmail.com.

How to Use msCron:

  Intialization:
  
      $(element).msCron();
      
  Getting Cron Expression:
  
     var cron = $("element").msCron();
     
    alert(cron.getCron )  //you can get the required CRON expression
    
  Setting CRON Expression:
  
    $("element").msCron({
        setCron: “0 0 12 1/1 * ? *”
        activeTab: “DAILY”
    });
    
activeTab  is MINUTES / HOURLY / DAILY / WEEKLY / MONTHLY / YEARLY 

