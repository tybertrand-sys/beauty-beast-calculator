# Beauty & Beast Wellness Dosage Calculator — Private Version 1.1

This is a working offline Progressive Web App (PWA) designed for private household use.

## Included
- Dose-to-syringe-unit calculator
- Reconstitution concentration calculator
- Blend component calculator
- Mass and volume unit converter
- Show My Math
- Saved calculation history
- Editable Beast and Beauty personal protocols
- Shared vial tracking
- Reference-name library
- Dark/light mode
- Local-device storage
- JSON backup and restore
- Offline service worker
- Installable PWA manifest

## Important limitation
This app performs calculations only from values entered by the user. It does not choose or recommend a dose. No personal dosage schedule is preloaded because exact private protocol values were not supplied in the project files.

## Run it
Host the folder on GitHub Pages or another HTTPS web host. Open the hosted site in Chrome, then choose **Add to Home screen** or **Install app**.

For quick local testing, open `index.html`, although service-worker installation requires HTTPS or localhost.

## GitHub Pages
1. Upload all files and folders to the root of your repository.
2. In GitHub: Settings → Pages.
3. Set Source to **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`.
5. Save and wait for the site link.

## Data privacy
All app data stays in browser local storage unless the user exports a JSON backup.


## Version 1.1 additions
- Preloaded Beast and Beauty protocol records from the supplied protocol sheets
- Tap any protocol phase to auto-fill the calculator
- Beast/Beauty profile switch
- Local reminder and alert center
- Optional browser notifications
- Reminder repetition: one-time, daily, weekly, or Monday/Wednesday/Friday

### PWA alert limitation
This build checks reminders while the app is open and can show browser notifications while active. Reliable closed-app scheduled notifications are restricted by Android/browser behavior and are a later APK-packaging enhancement.


## Version 1.2 additions
- Dashboard 2.0 with profile-aware greeting and at-a-glance summary
- Today's reminders panel
- Current protocol phase panel with one-tap calculator loading
- Inventory dashboard with low-vial status
- Recent calculation panel
- Quick actions
- Current protocol phase tracking and progress bars
- Typical-dose inventory estimates
- Estimated doses remaining
- Date-opened and low-warning thresholds for vials
- Automatic migration of Version 1.1 local data


## Version 1.3 additions
- Record a protocol dose directly from the current protocol card
- Automatically reduce a matching tracked vial
- Private activity log with timestamp, profile, phase, syringe units, and inventory change
- Recent dashboard feed now combines calculations and recorded protocol activity
- Dedicated Settings screen
- PWA install button and installation guidance
- Theme control in Settings
- Backup, import, and complete data reset controls
- Clear explanation of Samsung Face Unlock versus later in-app APK biometric authentication
- Automatic migration of Version 1.2 local data


## Version 1.4 additions
- Online/offline status badge
- Safer calculator warnings for results near or above syringe capacity
- Searchable saved-calculation history
- Beast/Beauty activity filtering
- Better confirmation before deleting personal protocols
- PWA update-ready messages
- Accessibility focus improvements
- Reduced-motion support
- App version and storage information in Settings
- Final release-candidate polish and validation improvements


## Version 1.5 additions
- First-run onboarding for choosing the default Beast or Beauty profile
- Copy calculator result and Show My Math to the clipboard
- One-tap reminder setup from the current profile's protocol
- CSV export for activity records
- CSV export for saved calculation history
- Improved reset behavior that relaunches guided setup
- Version 1.5 release labeling and cache update


## Version 1.6 additions
- Fixed protocol editing so changing one phase no longer deletes the remaining saved phases
- Custom protocol editor now supports vial amount, liquid volume, step label, dose, units, and guidance
- Automatic syringe-unit calculation for custom protocol steps when enough values are supplied
- Undo the most recently recorded dose and restore its prior vial inventory
- Manual positive or negative vial inventory adjustments
- Restore original Beast and Beauty protocols without deleting custom protocols
- Stronger local-data migration and factory-protocol recovery
- Version 1.6 cache and release labeling


## Version 1.7 additions
- Build a batch reminder schedule directly from a saved protocol
- Schedule frequencies: weekly, daily, Monday/Wednesday/Friday, or twice daily
- Printable black-and-white protocol summary for Beast and Beauty
- Snooze any reminder for one hour
- Reminder list automatically sorts by next due time
- Vial inventory preview before saving manual adjustments
- Version 1.7 cache and release labeling


## Version 1.8 additions
- Record a dose directly from the calculator
- Automatically reduce a matching tracked vial for manually calculated doses
- Edit existing reminders
- Cancel reminder editing without losing saved reminders
- Activity totals for all time, this week, and the selected profile
- Settings data check for missing protocol values, invalid vial inventory, and incomplete reminders
- Version 1.8 cache and release labeling


## Version 1.9 additions
- GitHub Pages automatic deployment workflow
- Deployment checklist for uploading the extracted source correctly
- 404 redirect fallback
- Export and import personal protocols separately from full backups
- Browser storage usage checker
- Built-in application self-test
- Global error banner that preserves saved data and reports unexpected failures
- Version 1.9 cache and release labeling


## Version 2.0 additions
- Consolidated release-candidate build
- Data schema Version 2
- Automatic safety snapshots before imports, resets, and protocol restoration
- Restore-last-snapshot control
- Safer full-backup validation
- Final release readiness check
- Version metadata and release notes
- Version 2.0 cache and release labeling


## Version 2.1 additions
- Mark reminders complete
- Reopen completed reminders
- Automatically schedule the next occurrence when a repeating reminder is completed
- Active, due/overdue, completed, and all reminder filters
- Reminder status totals
- Completed reminders no longer trigger alerts
- Dashboard ignores completed reminders
- Reminder completion state migration for existing Version 2.0 data
