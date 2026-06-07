# Happy Path 
--------------------------------------------------
### TC_ID: TC_HP_01
Title: Aliexpress Welcome
Steps:
1. Open Aliexpress App
2. Tap "Enable all notifications"

Expected Result:
- Image of a smartphone with a gradient screen (top section, centered)
- Title: "Receive timely notifications" (centered, below the image)
- Text: "Keep track of your orders and be the first to know about exclusive discounts by enabling all notifications. You can modify your notification settings at any time." (centered, below the title)
- Button: "Enable all notifications" (centered, bottom section, primary)
- Button: "Get order updates" (centered, below primary button, secondary)
- Option: "No thanks" (centered, below buttons, text link)
  
--------------------------------------------------
### TC_ID: TC_HP_02
Title: Choose country
Preconditions:
- App is opened
- Notifications already enabled

Steps:
1. Tap button "Your Location"
2. Choose Country
3. Tap button "Continue"

Expected Result:
- Window "Select country/region" pops up with the list of countries available
- Window "Welcome to Aliexpress" is shown with the selected country 
- User navigates to next screen
--------------------------------------------------
### TC_ID: TC_HP_03
Title: Sing In Credentials
Preconditions:
- App is opened
- Notifications already enabled
- Country Selected

Steps:
1. Tap on textbox "Email or phone number"
2. Enter valid email
3. Tap on button "Continue"
4. Tap on textbox "Password"
5. Enter valid password
6. Tap on button "Sing In"
   
Expected Result:
- Window "Welcome to Aliexpress" with textbox Email and Password filled.
- Button "Sing In" enabled 
- User navigates to next screen


--------------------------------------------------
# Alternative Scenarios 
--------------------------------------------------

### TC_ID: TC_NOTIF_BTN_02
Title: Get Order Updates
Steps:
1. Open Aliexpress App
2. Tap "Get order updates"
3. Accept OS permission (if prompted)

Expected Result:
- Permission popup appears (if needed)
- Only order updates notifications enabled
- User navigates to next screen
- Preference saved

--------------------------------------------------

### TC_ID: TC_NOTIF_BTN_03
Title: No Thanks
Steps:
1. Open Aliexpress App
2. Tap "No thanks"

Expected Result:
- No permission popup
- Notifications remain disabled
- User navigates to next screen
- Preference saved (opt-out)


