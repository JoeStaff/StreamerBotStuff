#TTS Chat
Streamer.bot Version 0.2.1 - Might work for others, but not supported.
This function is meant to send viewer chat to Speaker.Bot to be made into TTS audio. Includes !ttsban and !ttsunban to control which users won't have their text spoken allowed, as well as various settings to control who will have their text spoken.
Settings found in TTS Chat under Actions:
Everyone Allowed - If true, will ensure all users (minus Blacklisted) will have TTS
Subscribers Allowed - If true, will ensure subscribers will have TTS, regardless if Everyone Allowed is true or not
Moderators Allowed - Same, but for moderators
VIP Allowed - Same, but for VIP
Blacklist Never Allowed - if FALSE, blacklisted users will have TTS
Include Emotes - if true, emojies and emotes will be sent to Speaker.bot to be read as text
Voice Alias - The Voice Alias to be used, created on Speaker.bot
Pretext - Text that always appears before a users text
Post Text - Text that always appears AFTER a users text


How To Install:
Step 1 - In Streamer.bot, open dropdown menu located in the top left.
Step 2 - Click Import
Step 3 - Copy code from import_code.txt and paste into the Import String box
Step 4 - Click Import 
    it will warn you if actions with same name exist, asking to overwrite. 
    If you haven't already imported THIS code before, say no and create backups.
Step 5 - Under Actions tab, in the TTS Chat group, click on TTS Chat and modify the settings under Sub-Actions as desired.
    Be sure to modify %Voice Alias% to whatever your Speaker.bot is using
Step 6 - No resets required, you should be free to begin using it. Right click 'Chat Message' under Triggers and click Test Trigger
