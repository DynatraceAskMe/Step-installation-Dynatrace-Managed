# Step-installation-Dynatrace-Managed
setup your Dynatrace Managed cluster step by step,follow the steps below.

## Dynatrace managed hardware requirement
Please click this link [Dynatrace managed hardware requirement](https://www.dynatrace.com/support/help/shortlink/managed-requirements)


1. You can download Dynatrace install file from the e-mail Dynatrace send to you.

    [![Screen-Shot-2564-09-23-at-17-43-49.png](https://i.postimg.cc/k40rsRyH/Screen-Shot-2564-09-23-at-17-43-49.png)](https://postimg.cc/ZBxDKR2P)
    
2. Connect to your Dynatrace managed server and then run command install /bin/sh dynatrace-managed (Dynatrace Managed version).

    [![Screen-Shot-2564-09-23-at-17-49-37.png](https://i.postimg.cc/kGHyKWFV/Screen-Shot-2564-09-23-at-17-49-37.png)](https://postimg.cc/m1QMGznR)

3. Input command **Agree**

    [![Screen-Shot-2564-09-23-at-17-55-18.png](https://i.postimg.cc/3rGjc0BZ/Screen-Shot-2564-09-23-at-17-55-18.png)](https://postimg.cc/mhbFcDKc)

4. If you want to change the directory path, please input directory path and if want the default directory path, please click **Enter**.
      #### Default settings
        Installation path (binaries): /opt/dynatrace-managed
        Dynatrace Server data files: /var/opt/dynatrace-managed

    [![Screen-Shot-2564-09-23-at-17-58-14.png](https://i.postimg.cc/T1mgBBv9/Screen-Shot-2564-09-23-at-17-58-14.png)](https://postimg.cc/fSzV92Lt)
    
    [![Screen-Shot-2564-09-23-at-18-07-07.png](https://i.postimg.cc/1zwSnHSd/Screen-Shot-2564-09-23-at-18-07-07.png)](https://postimg.cc/67WgFCyV)
    
5. If you want to customize path, enter **N**, if you don't want to customize path, enter **Y**.  
    a.	metrics repository (used for keeping data such as long-term metrics, and configuration)  
    b.	Elasticsearch store (used for keeping data such as real user session analysis, visit, user action)    
    c.	raw transaction store (used for keeping data such as transaction, code level)  

    [![Screen-Shot-2564-09-23-at-18-19-07.png](https://i.postimg.cc/26871CLX/Screen-Shot-2564-09-23-at-18-19-07.png)](https://postimg.cc/7Cd2c8Vg)
    
    [![Screen-Shot-2564-09-23-at-18-19-37.png](https://i.postimg.cc/QdQQSFpy/Screen-Shot-2564-09-23-at-18-19-37.png)](https://postimg.cc/k25RgXYQ)
    
    [![Screen-Shot-2564-09-23-at-18-19-47.png](https://i.postimg.cc/k57xH7sX/Screen-Shot-2564-09-23-at-18-19-47.png)](https://postimg.cc/qNZhhVW9)
    
    [![Screen-Shot-2564-09-23-at-18-22-15.png](https://i.postimg.cc/9QLGsvnd/Screen-Shot-2564-09-23-at-18-22-15.png)](https://postimg.cc/4Yh79FZy)
    
 6. If you don't have a name group **Enter** and if you have a name group, please input name group. 

    [![Screen-Shot-2564-09-23-at-18-27-39.png](https://i.postimg.cc/Vvcw1ZVg/Screen-Shot-2564-09-23-at-18-27-39.png)](https://postimg.cc/XGxmkL3B)
    
 7. Enter **N**
 
    [![Screen-Shot-2564-09-23-at-18-28-55.png](https://i.postimg.cc/HkJTwMXQ/Screen-Shot-2564-09-23-at-18-28-55.png)](https://postimg.cc/mPsxRtdD)
    
 8. Input your Dynatrace license.

    [![Screen-Shot-2564-09-23-at-18-32-17.png](https://i.postimg.cc/bN9mmVHP/Screen-Shot-2564-09-23-at-18-32-17.png)](https://postimg.cc/3dWjRBcf)
    
 9.  **Enter**

   [![Screen-Shot-2564-09-23-at-18-34-34.png](https://i.postimg.cc/kXN7fCp5/Screen-Shot-2564-09-23-at-18-34-34.png)](https://postimg.cc/D8ZVw9FV)
   
 10. Wait, Dynatrace installing. 
 
  [![Screen-Shot-2564-09-23-at-18-43-36.png](https://i.postimg.cc/prJKBT5H/Screen-Shot-2564-09-23-at-18-43-36.png)](https://postimg.cc/RJq3SvTs)
  
 11. Install Dynatrace managed success.

  [![Screen-Shot-2564-09-23-at-18-38-10.png](https://i.postimg.cc/TwkkJCz0/Screen-Shot-2564-09-23-at-18-38-10.png)](https://postimg.cc/WFk626bq)

 12. Https:// <IP> on web browser and then input information, ann then click **Next**
  
  [![Screen-Shot-2564-09-23-at-18-46-08.png](https://i.postimg.cc/x8XSvk4k/Screen-Shot-2564-09-23-at-18-46-08.png)](https://postimg.cc/64xSwQww)
  
  

  # References:   
[Set up a cluster | Dynatrace Documentation ](https://www.dynatrace.com/support/help/shortlink/managed-cluster-setup)

