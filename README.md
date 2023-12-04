# IM_Image_Dataset
IM Image Dataset for Multimedia Forensics

## Configuration
This repository contains two sets of image datasets for 20 Instant Messaging applications (IM): Single Share Dataset and Double Share Dataset.

### Single Share Dataset
The IM applications included in the Single Share Dataset are:

- Band
- Discord
- Element
- Google Chat
- KakaoTalk
- Line
- Messenger
- QQ
- Session
- Signal
- Skype
- Slack
- Snapchat
- Teams
- Telegram
- Threema
- Viber
- WeChat
- WhatsApp
- Wire
- Original

#### Single Share Dataset Overview
- Total number of images: 5,152
- Each image is generated using the editing and quality options provided by each IM application.
- The images are organized in folders corresponding to each IM application.
- The image filenames follow the format: {OS}\_{QualityOption}\_{EditingFlag}.jpg
- The 'Dataset.csv' file contains the extracted features from the dataset.

### Double Share Dataset
Using the Single Share Dataset, 20 images each were re-shared to each 20 IM application using Android and iOS.

#### Double Share Dataset Overview
- Total number of images: 16,000
- Each image is generated using the default quality options provided by each IM application and is created without additional editing.
- The images are organized in the corresponding folder for each IM application and are in the form: {OS}\\{First Shared IM}\\{First Shared IM}-{Last Shared IM}
- The image filenames follow the format: {First Shared OS}-{Last Shared OS}\_{QualityOption}\_{EditingFlag}.jpg
