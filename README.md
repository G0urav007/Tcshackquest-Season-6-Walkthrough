# Tcshackquest-Season-6-Walkthrough
 <img width="1280" alt="Screenshot 2021-11-15 at 11 44 56 AM" src="https://user-images.githubusercontent.com/82142638/141731756-06bf5851-735e-4552-8a43-cd35f9a6106f.png">

# Let's start with first one >> { JS MASTER }

## Overview :

Point > 100 

## Description :

Time to play with JS

## Hint :

Can you recover the key hiding in plain sight?

## Approach :

01 : https://play.tcshackquest.com/jstime 

The link goes to something that looks like this:

<img width="1280" alt="Screenshot 2021-11-15 at 11 57 10 AM" src="https://user-images.githubusercontent.com/82142638/141732995-488f5b0b-9c48-4127-ab16-2dfe08f8c9eb.png">

02 : go to view page source..

<img width="1280" alt="Screenshot 2021-11-15 at 12 00 37 PM" src="https://user-images.githubusercontent.com/82142638/141733323-bda9aa78-0699-45ee-82fb-6b84dd4a5c9d.png">

03 : After, seeing the source code Script i got to know the encryption is base64.

<img width="1278" alt="Screenshot 2021-11-17 at 8 42 58 AM" src="https://user-images.githubusercontent.com/82142638/142127965-67ac04b5-b775-4ebe-8a08-6d7c05231505.png">

04 : i got the key here .. just copy paste here ..

<img width="1280" alt="Screenshot 2021-11-17 at 8 44 18 AM" src="https://user-images.githubusercontent.com/82142638/142128075-cc5cbc7f-d2ef-484d-a940-a5a793a1a243.png">

### BOOM ..!!



# Second >> { The Flash } 

## Overview :

Point > 100 

## Description :

I'm Barry Allen and I'm the fastest man alive.

## Hint :

Iris and Flash are playing a hide and seek game. Flash being the fastest man alive is not visible to Iris. Can you help Iris spot Flash?

## Approach : 

01 : https://play.tcshackquest.com/catchme?uuid=10

The link goes to something that looks like this:

<img width="1280" alt="Screenshot 2021-11-17 at 8 49 49 AM" src="https://user-images.githubusercontent.com/82142638/142128664-a9f1cf56-cfc2-43dc-b7d0-6a78e335f0c7.png">

02 : follow simple steps just intercept the request in burp suit..

<img width="1280" alt="Screenshot 2021-11-17 at 8 54 40 AM" src="https://user-images.githubusercontent.com/82142638/142129076-637f1821-fa14-4651-a007-6d85521943d8.png">

03 : sent to intruder & select only uuid={10} for attack.

<img width="1280" alt="Screenshot 2021-11-17 at 8 59 17 AM" src="https://user-images.githubusercontent.com/82142638/142129498-0d9562bd-bf95-4212-bfcc-e54bc3a55f90.png">

see here ..!!

04 : Set payload numbers 00 - 10 to see the request and start attack.

<img width="1280" alt="Screenshot 2021-11-17 at 9 01 34 AM" src="https://user-images.githubusercontent.com/82142638/142129737-ef8e7a39-c4bd-4075-aef5-b926a7813ed7.png">
 
 Got the Flag in uuid = 5
 
### BOOM ..!!

