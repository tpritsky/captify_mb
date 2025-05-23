Requirements:

**On Opening**

- Splash Screen (PRIORITY - 1)
- Sign Up or Sign In (Already implemented -- whitelabel)

**Connection** 

- Search for Captify (PRIORITY - 1, but can be whitelabeled)
- Pair to Captify (PRIORITY - 1, but can be whitelabeled)
- Reconnect if connection is lost (PRIORITY - 1)
- Stay connected in the background (PRIORITY - 1)

**Tutorial** (PRIORITY - 2)

- Tutorial containing videos on how to use the glass (could also be overlays)

**Main Screen** (PRIORITY - 1, can whitelabel relevant components)

- Transcribe
    - Support for 40 languages
- Translate
    - Select between different language pairs

**History Page**

- List of conversation sessions (PRIORITY - 2)
- Conversation details (PRIORITY - 3) 
    - Share conversation 
    - Summarize conversation 
- Settings
    - [Toggle] Automatically save conversations (PRIORITY - 2, needed for list of conversation sessions)

**Settings**

- Subscription  (LATER - DO NOT IMPLEMENT)
    - Free / Paid tiers
    - Payment for paid tier 
- Transcription Mode (PRIORITY - 1)
    - Automatic (cloud+offline) 
    - Offline Only (less accurate)
    - Online only
- Microphone Settings
    - Source (PRIORITY - 1)
        - Captify’s mic
        - Phone mic
        - Bluetooth mic
    - Capture mode (for Captify’s mic) (LATER - DO NOT IMPLEMENT)
        - Beamforming
        - Omnidirectional
- [Toggle] One button transcribe (start transcribing immediately when turned on)  (PRIORITY - 1)
- [Toggle] Glasses sound effects  (PRIORITY - 1, already in the API)
- [Toggle] Speaker Labelling   (PRIORITY - 1 -- but captify team will test and provide the model to use)
    - Record 18s clip of person speaking
    - Option to not display my own voice transcription
- [Toggle] Transcribe phone calls (LATER - DO NOT IMPLEMENT)
- [Toggle] Environmental Sound Detection  (PRIORITY - 1 -- but captify team will test and provide the model to use)
    - Doorbell Ringing
    - Knocking
    - Baby Crying
    - Applause
    - Laughter
- Caption Settings  
    - Position (PRIORITY - 1)
    - Depth (LATER - DO NOT IMPLEMENT)
    - Speed (PRIORITY - 1)
    - Text Size (PRIORITY - 1)
    - [Toggle] Translation: display original text (PRIORITY - 1, already implemented in demo app)
- Display Settings (PRIORITY - 1, already implemented in demo app)
    - Brightness
    - Auto-Off
- Glasses Language (PRIORITY - 1, already implemented in demo app)
- About Glasses (PRIORITY - 1, already implemented in demo app)
    - Firmware version
    - Serial number
    - MAC address
    - Name (rename)
- Account (PRIORITY - 2, already implemented in demo app, but Jason needs to provide their backend code)
    - Name
    - Email
    - Change Password

**Firmware Update**

- OTA update (PRIORITY - 1, already implemented in demo app, but Jason needs to provide trheir backend code)
- Usage analytics (PRIORITY - 1)
---

Advanced:

SDK for developers to develop on Captify**** (LATER - DO NOT IMPLEMENT)
