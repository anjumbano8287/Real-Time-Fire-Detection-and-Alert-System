# Real-Time-Fire-Detection-and-Alert-System
Developed a real-time fire detection and alerting system built using YOLO (You Only Look Once) for object detection, Flask for location integration, and Twilio for emergency SMS and call alerts. It also features camera tampering detection, severity classification, and bilingual evacuation alerts using Google Text-to-Speech (Hindi + English).

🚀 Features ✅ Real-time fire detection using YOLOv8 Model

📊 Severity classification: LOW, MEDIUM, HIGH

🔁 Frame skipping and optimization for fast detection

🔉 Siren and bilingual evacuation announcements (Hindi & English)

📱 Twilio-based emergency SMS alerts and voice calls

📷 Camera tampering detection (black screen, frozen, unplugged)

🌐 Location-based alert with OpenStreetMap link

🧠 Flickering brightness logic to avoid false positives

🖥️ Tech Stack Computer Vision: OpenCV, YOLOv8 (ultralytics)

Backend-Flask

Important teck stack for this project
💻 Tech Stack



Category	                        Tools & Libraries


👁️ Computer Vision              	OpenCV, YOLOv8 (Ultralytics)




⚙️ Detection Logic              	Frame skipping, brightness flicker filtering



🔊 Audio Alerts	                  gTTS (Google Text-to-Speech), playsound




🌐 Location & Maps              	OpenStreetMap (for sending location-based alert link)


📱 Emergency Alerts	              Twilio (SMS & Voice Calls)


🧠 Language Support	              Multilingual announcements (Hindi & English)


🛡️ Tampering Detection	          Black screen, frozen feed, and unplugged camera logic


🐍 Programming Language	          Python



Required python Libraries need to install



ultralytics           # For YOLOv8



opencv-python         # For real-time video processing



numpy                 # For array and image operations



gTTS                  # Google Text-to-Speech for bilingual announcements



playsound             # To play audio alerts



twilio                # For SMS and voice call alerts



requests              # To interact with external APIs (e.g., location)



langdetect            # For multilingual detection (if needed)




Thankyou for watch 
