# 7erfa-App
## Flutter-Firebase mobile app for seamless customer-craftsmen connection
### Table of Contents
- [Main Features](#Main-Features)
- [More details](#more-details)
- [Getting Started](#section-1)
- [Usage](#section-1)
- [Demo Video](#section-1)
- [Contributing](#section-1)
- [License](#section-1)

#### Main Features
• *Authentication*  
• *in_App Camera, open gallery*  
• *Request location permission, using reverse geocoding api*  
• *Integration with Google Maps*  
• *Search and Filter*  
• *handle customers reservations using FireStore*  
• *in-App chat*  
• *Rating and Review*  
• *Craftman profile*  
• *QR Code Confirmation*  

#### More details
##### • Authentication 
remember password - reset password - mobile OTP Verification
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/a8ba864a-b5ab-43b4-a6d2-db329d1fdc24" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/3160cacf-c168-44e4-a0c5-7c2f9e80c9cd" width ="200">
</div>  

##### • in_App Camera, open gallery  
one of auth steps is to allow users (customers & craftsmen) to take profile pictures using in-App camera or open gallery to choose one  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/3a2d4c42-abc0-40da-8aa6-126d3f737326" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/fd26a03b-8e5a-4389-9fcd-6e6037926a87" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/8ec7385c-ced8-4944-8684-e7ae006d19e9" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/d5c1835c-b350-4c9b-bde7-a960b5be9836" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/ad6eeca6-6e2a-49a7-a107-da7bc46d2677" width ="200">
</div>  

also allow craftsmen to take picture for there work shops  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/5f037abd-2b04-4e7c-87cd-26f3adbfd8de" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/53021317-0ae2-4a92-a000-6e183deaeff4" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/9d6c055b-2c65-4d1f-9407-907b0953d9ef" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/308bb785-e112-4878-bee5-0694ef468951" width ="200">
</div>  

##### • Request location permission, using reverse geocoding api 
ask user for allowing app to access his location .. so getting his latitude and longitude then reverse it to address by reverse geocoding api to display user current location as address  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/7728aa21-36f5-4fff-9e40-34a0936e5003" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/ee784334-d530-4c16-ba50-a96d0bac9928" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/421a7364-8ccd-4e74-aafe-ea260e5eb32c" width ="200">
</div>  

##### • Integration with Google Maps  
To enable craftsmen to select the location of their workshops within a specific area, the choice is determined based on the craftsman's current location, where the designated area takes the form of a circular region with a specified radius, centered around the user's current position.  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/d8618cf6-04dc-49ea-a393-235eed6ee615" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/1b72677d-f0dc-4aba-b153-17f871e7a01f" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/e0683fda-e178-48ae-98dc-8c2b40a51189" width ="200">
</div>  

##### • Search and Filter  
allows customers to search for craftsmen, and filter the result by nearest or Highest rating.  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/9a9e1ec3-b480-4e2a-8fca-e951f65df149" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/63bce6e7-0060-4761-99ea-ccb7454dfad7" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/eca62031-a80f-4a6e-82ff-fd0db68dc81f" width ="200">
</div>  

##### • handle customers reservations using FireStore
-customer can send reservation for craftman  
<img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/dea605b5-1631-4740-92b9-1c063ac86771" width ="200">  
-craftman can accept or deny the reservation  
<img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/e8f5e302-21df-4104-8e2a-c0c89c7f92c7" width ="200">  
-reservations ordered by date  
<img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/ffeb4e8d-c656-453f-90ac-25e122a371dd" width ="200">  
-When the craftsman completes the job, the customer must confirm the job's completion first  
    • craftsmen side  
 <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/3a61b9c9-82a3-496e-a99b-5404c3132419" width ="200">  
    • customers side  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/0e574958-67b8-4def-b07d-c4e842102edf" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/9f0bf2dc-16fe-4387-b1bf-8e2bfeeccb46" width ="200">
</div>  

-Prevent reservation spam: Customers cannot reserve a craftsman if their ongoing  

<img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/25e23799-a63c-4fbd-8e4f-f3e07634e833" width ="200">  

##### • in-App chat  
customer can communicate with craftsman through an in-app chat.  
<img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/c3822b2d-6a5b-4ea2-8410-bd1b4735f4b7" width ="200">  

##### • Rating and Review  
customer cannot confirm job completion until they have provided a rating for the craftsman  
<div>
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/831a8664-bc3b-4654-98f4-34d0a4904347" width ="200">
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/b1ffb02a-571f-4abb-a60b-48f3205cb401" width ="200">
</div>  

##### • Craftman profile  
each craftman has profile which contain his workshop,photos for his work and all customers rating and reviews  
 <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/8952471d-15fc-498f-a0a3-f117f0845216" width ="200">  

##### • QR Code Confirmation  
Each reservation has a unique QR code, displayed when craftman press on qr icon after confirming completion from customer. To verify the financial transaction, the customer must scan the craftsman's QR code on his mobile app, streamlining the reservation removal process  
     • craftsmen side  
 <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/6c74501a-8c75-451b-b39c-800f43026f0a" width ="200">  
     • customers side  
  <img src="https://github.com/AliEl-Saka/7erfa-App/assets/125530187/f2497412-1dbf-40f0-b74c-ada1a7cbaced" width ="200">


 






