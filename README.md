# Mobile application testing    
1. Checklist for testing the core functionalities of the Shopping List mobile application, created by me based on the requirements analysis (includes both general checks for mobile applications and functional checks specific to the given application)  
https://docs.google.com/spreadsheets/d/1RqOpyV9k70hqCdnZXRogyqAEpvbnkOcxf2-wM2SkTVo/edit?usp=sharing

2. Test cases for testing the Shopping List mobile application, export from QASE      
https://github.com/VolhaPiatrova/mobile/blob/main/TestCasesMobileApp.pdf  

3. Bug reports export from YouTrack.     
https://github.com/VolhaPiatrova/mobile/blob/main/BugReportMobile.xlsx  

4. Test run results executed and exported from from QASE,     
https://github.com/VolhaPiatrova/mobile/blob/main/G10-Test%2Brun%2B2025_06_23_Mobile.pdf

5. Test summary report. A final report summarizing testing activities, results, and conclusions.    
https://docs.google.com/document/d/1rEIJWwRNX8ihsncX93Iw8ch5q1DWUI0HAO5oUxKTVx4/edit?usp=sharing  

6. Traffic Interception and Manipulation for "Online Store" Application.    
As part of the assignment, I performed network traffic analysis and manipulation for the "Online Store" application using Charles Proxy on both desktop and mobile devices. Tools Used: Charles Proxy (installed and configured on desktop and mobile), mobile and desktop browsers, video recording tools.  

     6.1. Desktop Scenario (intercepted and modified API requests in the browser). All actions were recorded and saved in a video file.   

- Changed the quantity of items in the cart from "2" to "500"
https://github.com/VolhaPiatrova/web/blob/main/%D0%A1hange_quantity_of_items_in_the_basket.mp4  
- Simulated a 403 Forbidden status code for https://demoshopping.ru.
https://github.com/VolhaPiatrova/web/blob/main/Server_return_status_code_403.mp4  
- Redirected traffic from the production environment (https://demoshopping.ru) to the QA environment (https://qa.demoshopping.ru)
https://github.com/VolhaPiatrova/web/blob/main/Redirect_request_from_Prod_to_QA.mp4  

     6.2 Mobile Scenario (intercepted HTTPS traffic from a mobile browser)

- Modified a delete request to remove a different item from the cart.  
https://github.com/VolhaPiatrova/mobile/blob/main/Delete_item.mp4

- Simulated image injection upon visiting https://demoshopping.ru.  
https://github.com/VolhaPiatrova/mobile/blob/main/Picture_in_browser.mp4
