# CollegeMate — GitHub APK Build

This is the GitHub-ready Android wrapper for the CollegeMate day-wise attendance web app.

## What is included

- Day-wise attendance only
- Present / Absent / Holiday
- Automatic attendance percentage
- Recent attendance history
- Calendar view
- Offline local storage
- Professional CollegeMate UI with rounded cards, gradient calendar header, refined typography, and an About section
- No subjects
- No tasks
- No homework
- About section describing the app
- Creator attribution: Created by Karan

## Build the APK on GitHub — no Android Studio

1. Create a new **public or private** GitHub repository, for example `CollegeMate-Attendance`.
2. Upload all files and folders from this project to the repository. Keep `.github/workflows/build-apk.yml` in exactly that location.
3. Open the repository's **Actions** tab.
4. Select **Build CollegeMate APK**.
5. Click **Run workflow** (or push to `main`, which also starts the workflow).
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run and scroll to **Artifacts**.
8. Download **CollegeMate-Attendance-APK**.
9. Extract the downloaded artifact and install `CollegeMate-Attendance.apk` on your Android phone.

The APK built by this workflow is a debug APK and is suitable for installing/testing on your own phone.

## App ID

`com.collegemate.attendance`

## Important

Attendance data is stored locally on the device/browser storage. It does not automatically sync between your laptop and phone.
