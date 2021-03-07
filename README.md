# Retrieve-file-from-firebase-storage-and-Display-using-asynctask
Store the PDF file into firebase Storage and fetch it and Display PDF using pdfviewer


![](https://user-images.githubusercontent.com/46309253/62010393-ec9e2800-b187-11e9-83ca-87cb53fd7392.gif)

  # Steps 
- Setup Firebase accounta and add your project.(Must Add google-services.json file )
- in Firebase Click on "Storage" from left Menu
- than add your PDF files 
- click on uploaded file than you will get link of that pdf file just copy and paste into your recyclerview
- after that in your android project create recycleview or use listview to view data
- use PDFviewer library and AsyncTask to Load and Display Data 

# IMP link
- Firebase Setup: (https://firebase.google.com/docs/android/setup)(url)
- Firebase dependency : (https://firebase.google.com/support/release-notes/android)(url)

# Dependency in project:
- Firebase Core:	'com.google.firebase:firebase-core:17.0.1'
- Analytics:	com.google.firebase:firebase-analytics:17.0.1
- Cloud Messaging:	com.google.firebase:firebase-messaging:19.0.1
- Cloud Storage:	com.google.firebase:firebase-storage:18.1.1
- In-App Messaging:	com.google.firebase:firebase-inappmessaging:18.0.2
- In-App Messaging Display:	com.google.firebase:firebase-inappmessaging-display:18.0.2

## Note: If your Are using the new version of library than you may get Error of AndroidX.
## Solution:You need migrate project into AndroidX.


# If You have Any Queries About this Comment it in details





