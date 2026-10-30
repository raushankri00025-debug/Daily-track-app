StudyLife Tracker Android Project

मोबाइल से APK बनाने के चरण:
1. ZIP को Files ऐप से Extract करें।
2. GitHub पर StudyLifeTracker नाम का नया repository बनाएं।
3. Extract किए गए सभी files/folders upload करें; .github hidden folder भी शामिल करें।
4. Commit करें, फिर Actions tab खोलें।
5. Build StudyLife Tracker APK workflow चुनकर Run workflow दबाएं।
6. सफल build के बाद StudyLifeTracker-debug-apk artifact डाउनलोड करें और ZIP extract करें।
7. app-debug.apk पर टैप करके install करें। जरूरत हो तो Android Settings में उस ऐप को install permission दें जिससे APK खोला है।

यह debug APK है, Play Store release-signed APK नहीं। डेटा इसी डिवाइस में सेव होता है; समय-समय पर डेटा बैकअप डाउनलोड करें।
