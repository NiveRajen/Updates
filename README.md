# Updates

iOS 17
1. Interactive Widgets - iOS 17 introduced interactive widgets, allowing users to interact directly with widgets on the Home Screen, Lock Screen, and StandBy mode. Developers can now implement buttons, sliders, and other controls in widgets, making them more dynamic and functional. Framework: WidgetKit - originally introduced in 14.0
https://developer.apple.com/documentation/widgetkit/adding-interactivity-to-widgets-and-live-activities, https://www.youtube.com/watch?app=desktop&v=UsIeymtCFaA

2. StandBy Mode - StandBy Mode is a new feature that turns your iPhone into a smart display when charging in landscape mode. It can show the time, photos, widgets, or other interactive content, making the iPhone a useful hub while sitting on a desk or charging station. Framework: UIKit (with additions for StandBy).
https://www.youtube.com/watch?v=4djD8HQLffc

3. Live Activity - With iOS 17, Live Activities (originally introduced in iOS 16) have become more interactive. Live Activities allow users to view real-time updates on the Lock Screen, such as sports scores, delivery tracking, or ongoing workouts, without opening the app. https://developer.apple.com/documentation/activitykit/displaying-live-data-with-live-activities.

4. Vision Framework Enhancements
Framework: VisionKit
In iOS 17, the Vision framework received several updates to improve image processing and machine learning tasks, such as detecting objects and performing image segmentation.This includes text recognition, barcode scanning, and object detection.
Key Features:
- Enhanced text recognition and object detection.
- Ability to process images and video for augmented reality (AR) experiences.
- Improved performance in analyzing images for custom ML models.

5. CoreML Enhancements
Framework: CoreML
Apple continues to refine CoreML for on-device machine learning. With iOS 17, CoreML got better performance and support for new ML models, making it easier to integrate ML-based features into apps without relying on a server.
Key Features:
Expanded support for running larger models on-device with better performance.
Enhanced integration with other iOS frameworks like Vision and ARKit for more sophisticated ML-based features.

6. Live Voice Mail - his new framework allows for real-time transcription of voicemails. As a voicemail is being left, users can see the transcription and decide whether they want to pick up the call mid-message.Framework: LiveVoicemail
https://www.youtube.com/watch?v=tsqWrEtb_fY

7. Contact Posters: OS 17 introduces Contact Posters, which allows users to create custom contact cards with personalized photos, fonts, and colors. These posters are shown when calling or texting others. Framework: ContactsUI https://www.youtube.com/watch?v=DfTr83YTRGM

8. AirDrop Enhancements: New ways to share content with others via AirDrop, including name-drop for transferring contact information by holding iPhones near each other. https://support.apple.com/en-gb/guide/iphone/iphcd8b9f0af/ios.

9. Journal App: A new app designed to help users reflect and record thoughts, memories, and activities, with suggestions powered by on-device intelligence. https://apps.apple.com/de/app/journal/id6447391597

10. New Siri Features: You can now activate Siri without saying "Hey Siri", just by saying "Siri" or simply by pressing a button.

11. Improved Autocorrect: Significant improvements to autocorrection, smarter text predictions, and more accurate text inputs. https://www.youtube.com/watch?v=IzzYfE2bWwI.
    
12. Audio Framework Updates (AudioToolbox & AVKit)
Framework: AudioToolbox, AVKit
Description: New updates to the AudioToolbox and AVKit frameworks in iOS 17 give developers more advanced control over audio and video playback, including background audio support, multi-device audio routing, and streaming media.
Use Case: Apps that handle media (e.g., music, podcasts, streaming services) can take advantage of these improvements for richer, more customizable audio and video experiences.

13. Networking Enhancements (Network)
Framework: Network and NetworkExtension
Description: Apple improved its Network framework in iOS 17 to provide better support for VPN configurations, secure network communication, and more flexible management of data across Wi-Fi and cellular networks.
Use Case: Developers can use these features to improve the security of networking features, such as secure communications or VPN functionality, and handle complex network environments more effectively.

14. Spatial Audio Support (AVFoundation & AudioKit)
Framework: AVFoundation, AudioKit
Description: iOS 17 introduced Spatial Audio support to a broader range of apps. This allows for dynamic, 360-degree audio experiences, enhancing immersive media playback.
Use Case: Developers building entertainment or media apps can use this feature to provide users with a more immersive audio experience, perfect for gaming, music, and video applications.

15. Focus Mode (Focus)
Framework: Focus
Description: Focus modes were expanded in iOS 17, allowing developers to build more granular control over notifications and app behavior, tailoring the user experience based on specific activities like “Work,” “Sleep,” or “Personal.”
Use Case: Developers can implement Focus mode filters in their apps, controlling notifications and content based on the user’s current activity, improving app interaction and reducing distractions

16. Privacy Enhancements (Privacy)
Framework: Privacy (Various updates to existing frameworks)
Description: iOS 17 introduces new privacy features such as more transparent app tracking and permissions, as well as stronger control over data shared with third-party apps. It also includes Private Browsing features in Safari and more.
Use Case: Apps can adopt these new privacy features to ensure they adhere to Apple's guidelines and improve user trust by making data privacy more transparent and user-controlled.

17. PDF Interactivity (PDFKit)
Framework: PDFKit
Description: PDFKit in iOS 17 received new capabilities for better interaction with PDF documents. You can now add interactivity such as forms and annotations more easily.
Use Case: Apps that work with PDF files, such as document management apps, can integrate these features for enhanced interactivity and user experience.

18. Health Data Enhancements (HealthKit)
Framework: HealthKit
Description: HealthKit received updates in iOS 17, adding new types of data (e.g., mental health, nutrition) that can be tracked within apps. It also introduced more robust features for sharing and managing health-related data.
Use Case: Developers can build apps that track new health metrics or provide users with richer health insights, improving wellness apps with better data privacy features.
