# PushAlertMechanics
This project contains the inner logic of working with firebase push notifications.
In this project I am receiving the push from firebase and saving it in the database and displaying in the listview/recyclerview.
On Tapping of push notification launching the explicit activity rather than the default activity.

there are two types of messages we receive from the firebase 
1. notification
2. data 

notification can contain data and notification and displays notification when the app is in bgackground , on tapping of the notification the intent contains the data as extras.

using only data tag can the send the notification wheather the app is background or in the background .

Using raisflow orm database to save the notifications in the onMessageReceived callback.
