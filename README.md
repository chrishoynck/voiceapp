## Artemisia VoiceNet
Artemisia VoiceNet is a voice-based application designed for farmers in rural Mali. It serves as a platform for exchanging questions and answers, providing sales information, and accessing agricultural information about Artemisia, available in both French and English. This application is developed using VoiceXML and PHP in Visual Studio Code, with cloud-based data storage (Altervista) for recording interactions and system updates. The directory and file structure on Altervista automates the organization of content by language. The main application is hosted on Voxeo Evolution. Voxeo Evolution provedes the phone number and corresponding PIN to access Artemisia VoiceNet. 
The application settings of Voxeo Evolution are the following: 
- Application Name: ICT4D-Voice-App2
- Forms of language it supports: Voice Phone Calls
- Voice Application Type: Development, USA, VoiceXML, Nuance, US Development Phrophesy 19 VXML, ASR/TTS. 
- Voice URL: https://raw.githubusercontent.com/chrishoynck/voiceapp/main/mainvoice.xml

**Features:**

- Bilingual Support: Available in French and English, catering to a diverse user base.
- Voice Interaction: Users can ask questions, receive answers, provide sales information, receive sales information and access agricultural information through voice commands.
- User computer interaction: Users can interact with the application directly by pressing numbers, to navigate to the right menu.
- Storage hosted on Altervista: System maintainers can access and update recorded data in the cloud through Altervista.

**Versioning:** This project is in the early stages of development. The most recent commit on the main branch represents the current operational version.
How to Use

**To interact with Artemisia VoiceNet:**
1. Dial the phone number 800-289-5570 on Skype (free of charge).
2. Enter the PIN 9996143150.
3. Navigate through the menu by pressing digits 1-4.
4. You can return to the previous menu at any menu.
5. After recording, you may confirm and end the call, remake the recording, or delete it and return to the previous menu.
6. In case desired information is provided/gained, you can exit application by ending call.

**To manage application as Admin:**
1. Browse to the [Altervista Platform](https://s514.altervista.org/lf.pl?sid=f0cab20cb59cefba62a1e91adeb17b1a)
2. Login with the credentials, Username: ict4d and request password by sending a GitHub message.  
3. Navigate to application
4. Browse through the directories, translate ques

**To report bugs:** 

Bug reports will be habdled in a seperate report-bugs branch, to prevent interference with the main development of the application.The brances can be merged when the fix is completed and the main is stable.  

- Go to the [Issues](https://github.com/chrishoynck/voiceapp/issues) tab.
- Click on [New Issue](https://github.com/chrishoynck/voiceapp/issues/new/choose).
- Report its location, possibly the potential 
  solutions, and how to activate the bug, including steps to reproduce, expected behavior, and actual behavior of the bug. 
- label the bug with appropriate label: minor or critical.
- Only report new bugs—duplicates will not be considered.
- Each commit should focus on a single bug.

**To contribute enhancements or features:**
1. Commit your changes to the [Feature_Update](https://github.com/chrishoynck/voiceapp/tree/Feature_Updates) branch.
2. Include a detailed description of your changes and any new features.
3. Limit each commit to one feature or change for clarity and manageability.