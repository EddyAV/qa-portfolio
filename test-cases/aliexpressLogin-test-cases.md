# Happy Path 
--------------------------------------------------
### TC_ID: TC_AE_HP_01
Title: Enable All Notifications

Steps:
1. Open Aliexpress App
2. Tap "Enable all notifications"
3. Accept OS permission

Expected Result:
- Aliexpress App opens
- User allows notifications
- All notifications enabled
- User navigates to next screen

--------------------------------------------------
### TC_ID: TC_AE_HP_02
Title: Continue with Default Location

Preconditions:
- Aliexpress app open
- All notifications enabled

Steps:
1. Open welcome screen
2. Verify location is shown (e.g., Mexico)
3. Tap "Continue"

Expected Result:
- Screen "Welcome to Aliexpress" is shown
- Screen shows flag and country name in "Your location"
- User proceeds to next screen

--------------------------------------------------
### TC_ID: TC_AE_HP_03
Title: AliExpress Credentials

Preconditions:
- Aliexpress app open
- All notifications enabled
- Location selected 

Steps:
1. Tab on "Email or phone number" textbox and type valid email/phono number
2. Tap on button "Continue" 
3. Tab on "Password" textbox and type valid password
4. Tap "Sign In"

Expected Result:
- Textbox "Email or phone number" shows the users input
- "Continue" button is disabled until users input credential
- Textbox "Password" hides users input
- "Sign In" button is disabled until users input credential
- User proceeds to next screen


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


