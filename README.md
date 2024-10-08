# Setup
## Prerequisites
1. Install ALVR on Vision Pro: https://apps.apple.com/app/alvr/id6479728026
2. Set up the ALVR Streamer on a Windows PC: https://github.com/alvr-org/ALVR/wiki/Installation-guide
3. Install VRChat on the Windows PC: https://store.steampowered.com/app/438100/VRChat/
4. Install Xcode 16 with watchOS 11 support

## With Vision Pro, Windows PC, iPhone and Watch on the same network (ideally PC wired and Vision Pro on nearby Wifi 6 AP):
1. Open the watchOS app on iPhone and Watch.
2. Navigate to https://vrchat.com/home/avatar/avtr_48b3d7fc-9726-4268-acec-be823804cc65, login or create an account, and click "Switch to Avatar".
3. Start ALVR Streamer, SteamVR, and VRChat on the PC.
4. Start ALVR on Vision Pro. In the Advanced Settings, enable Chroma Keyed Passthrough, set Chroma Blend Distance Min/Max to 0.2/0.7, and set the Chroma Key Color to P3 3C7F46. Once a connection is established to the Streamer, press Enter.
5. Search for a world with AudioLink (necessary for some effects, but passthrough works anywhere), or join https://vrchat.com/home/world/wrld_a5e9ec13-36b1-4e63-ae0c-dab9023401f9.
6. Use the Watch's Digital Crown to adjust passthrough, and play with the buttons/switches to control the avatar's audio and visuals.


## How to use the iPhone app

![iPhone](./iphone.png)

Inpute the VRChat/OSC server IP here.


## How to use the Watch app

![Watch](./watch.png)

### **Passthrough/Spectrum Switch**  
- Currently does nothing but is planned to switch modes via knob aka digital crown in a future update.

### **P: Switch Particle Styles**  
- Use the "P" button to toggle between different particle styles.

### **L Switch: Toggle Music Loop**  
- The "L" switch toggles the looping of the background music on or off.

### **1-7: Sound Effects**  
- **1**: Plays sound effect 1  
- **2**: Plays sound effect 2  
- **3**: Plays sound effect 3  
- **4**: Plays sound effect 4  
- **5**: Plays sound effect 5  
- **6**: Plays sound effect 6  
- **7**: Plays sound effect 7
