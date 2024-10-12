# MySolat v2024


<center><img src="https://thumbs.dreamstime.com/b/muslim-doing-salah-salat-shalat-sholaat-sujud-vector-illustration-81762121.jpg"></img></center>


New and updated version of MySolat Project with:
- Qiblah Direction Helper
- New Bottom Navigation Bar
- Mosque Near By (Integrated with <a href="https://masjid.onrender.com">Masjid Locator Project</a>)
- Location based on GeoLocation Coordinate
- Musafir Reminder
- Background Location

## Screenshots

Here are some visuals to showcase the project:



### Main Screen
> Same UI design but improved in UX. <br>

> Daily hadith in future update.

<img src="https://github.com/wanZ772/mysolat_website/blob/master/documentation/Screenshot_2024-09-09-16-00-38-01.png" width="200" height="400" /> <img src="https://github.com/wanZ772/mysolat_new/blob/master/documentation/Screenshot_2024-09-09-16-01-54-33.png" width="200" height="400" />

1) Auto Detect GeoLocation
2) Keep update user's location in background

### Navigation Option
> Navigation Options.

<img src="https://github.com/wanZ772/mysolat_website/blob/master/documentation/Screenshot_2024-09-09-16-00-43-41.png" width="200" height="400" />

1) Let User to choose to navigate to Qiblah Compass or Mosques Near By
2) Available Options:
    - Qiblah Compass
    - Mosque Near By

### Qiblah Compass
> Detect direction of qiblah and helping user by asking to rotate anti-clockwise / clockwise.

<img src="https://github.com/wanZ772/mysolat_website/blob/master/documentation/Screenshot_2024-09-09-16-01-23-35.png" width="200" height="400" /> <img src="https://github.com/wanZ772/mysolat_new/blob/master/documentation/Screenshot_2024-09-09-22-29-35-77.png" width="200" height="400" /> <img src="https://github.com/wanZ772/mysolat_new/blob/master/documentation/Screenshot_2024-09-09-16-01-02-87.png" width="200" height="400" />

1) Qiblah Direction Helper
    - Rotate Anti-Clockwise
    - Rotate Clockwise
    - Perfect Angle
2) Color indicator:
    - <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Photo-green-23_10_2023.png" width="20" height="20" />`Green`: Kaabah / Qiblah
    - <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/archive/6/62/20150316140911%21Solid_red.svg/120px-Solid_red.svg.png" width="20" height="20"> `Red`: 0º / Perfect North Pole
    - <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/21/Solid_black.svg/120px-Solid_black.svg.png" width="20" height="20" /> `Black`: Other Angel

### Mosques Near By
> Locate and find user's location and search available mosque(s) near by based on radius accuracy setting

<img src="https://github.com/wanZ772/mysolat_website/blob/master/documentation/Screenshot_2024-09-09-16-05-31-42.png" width="200" height="400" /> <img src="https://github.com/wanZ772/mysolat_new/blob/master/documentation/Screenshot_2024-09-09-14-08-47-53.png" width="200" height="400" /> <img src="https://github.com/wanZ772/mysolat_new/blob/master/documentation/Screenshot_2024-09-09-14-08-58-00.png" width="200" height="400" />

1) Locate user's geo-location
2) Make API call to the server and show available mosque(s) near by user's location
3) Able to show mosque's information popup when user tapped to the location marker icon
4) Able to give user direction by redirecting user to google map
5) Default radius accuracy level: 0.04
    > Lower accuracy level: Smaller searching radius <br>

    > Higher accuracy level: Larger searching radius
6) Integrated with <a href="https://masjid.onrender.com">`Masjid Locator Project`</a> as backend.
    - Live Project At: <a href="https://masjid.onrender.com">`Masjid Locator`</a>
    - `Link`: *https://masjid.onrender.com*
### Settings
> New UI and options available

<img src="https://github.com/wanZ772/mysolat_website/blob/master/documentation/Screenshot_2024-09-09-16-01-35-38.png" width="200" height="400" />

1) Refresh Location
    - New version of MySolat doesn't require user to set location manually
    - Detect current user's geo location and update
2) Azan Reminder
    - Nothing new
3) Musafir Reminder
    - Detect distance between current user's location and hometown
    - Trigger notification if user eligible to perform jama' and qasar
4) Background Location
    - Set background location service on / off
    - Able to continuously update user's location
5) Near By Mosque Accuracy
    - Set search accuracy level

### Quran
> Digital quran based on webview from Quran.com

- Credit to 
<a href="https://quran.com">Quran.com</a>

