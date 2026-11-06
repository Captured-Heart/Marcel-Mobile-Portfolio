# Mobile-Developer-Portfolio

<p align="left">
  <img alt="Nkpozi_Marcel_cover" src="assets/github_cover.png" />
</p>

Hello and welcome! 👋🏾💜, I'm thrilled to have you here. This GitHub repository showcases my journey as a Flutter developer, featuring a curated collection of my projects, contributions, and learning experiences. As a Flutter Developer, having worked on projects varying from Fintechs 💵, Health⚕️, Logistics 🛵, e-Commerce 🚚, VoIP 📞, AI 🤖, and Religion ✝️ etc, am currently seeking remote or relocation opportunities. Feel free to browse through my projects, check out the code, and see what I've been working on. If you have any questions, or suggestions, or just want to say hi, don't hesitate to reach out ☎️ 📞!

<br/>

#

# 1. Rideflow Hubs <a href='https://play.google.com/store/apps/details?id=org.rideflow.hubs'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/us/app/rideflow-hubs/id6794044854'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

Rideflow Hubs is the customer and vendor app of the Rideflow logistics platform in Nigeria. Customers send packages across the city by picking a route, comparing independent riders with logistics companies, and tracking the delivery live, while vendors manage their inventory and incoming orders from the same app.

## (Demo)

<p align="left">
  <img src="assets/rideflow_hubs/rideflow_hubs_demo.gif" width="300" alt="Rideflow Hubs demo" />
</p>

[▶️ Watch the demo video (MP4)](assets/rideflow_hubs/rideflow_hubs_demo.mp4)

## Send anything, anywhere in the city, and watch it arrive.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/rideflow_hubs/hubs_home.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_hubs/hubs_route.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_hubs/hubs_explore.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/rideflow_hubs/hubs_orders.png" width="600" />
      </td>
    </tr>
  </table>
</div>

## Key Features

1.  Live Map & Route Pricing:

        - Google Maps home screen showing nearby bikes, buses and trucks in real time. Customers pick a pickup and drop-off, see the route polyline, and get an estimated fee they can adjust before requesting a rider.

2.  Independent Riders or Logistics Companies:

        - Customers choose between an independent rider and a verified logistics company, and can browse providers by category (bikes, buses, trucks, movers) with ratings, fleet size, average fee and average delivery time.

3.  Live Order Tracking (Live Activities & Live Updates):

        - Delivery progress on the iOS Lock Screen and Dynamic Island through a custom Live Activity plugin, and as an ongoing progress notification on Android, driven by server-sent events and push. Only a short order reference, status and ETA reach the lock screen, never personal details.

4.  Vendor Mode & Inventory:

        - Vendors get their own home screen to manage inventory and incoming delivery orders alongside the customer experience.

5.  In-App Chat, Rewards & Notifications:

        - Customers chat inside the app, earn a free delivery through the "5 + 1 Delivery Reward" programme, and get push notifications for every order update.

6.  Secure Sign-in & OTA Updates:

        - Google and Apple sign-in, deep links, Crashlytics and Analytics, and over-the-air patches with Shorebird.

## Tools

- Flutter/Dart 💙
- Google Maps (polylines, markers, real-time) 🗺️📍
- Riverpod for State Management 🚀
- REST API with Dio 🌐
- Server-Sent Events & Firebase Cloud Messaging 🔔
- iOS Live Activities / Android Live Updates (custom plugin) 🏝️
- Hive (Local Database) 📦
- Firebase (Crashlytics, Analytics, Messaging) 🔥
- Google & Apple Sign-In 🔐
- Shorebird (over-the-air updates) 🐦
- Optimized for iOS and Android 📱
  <br/>

#

# 2. Rideflow Riders <a href='https://play.google.com/store/apps/details?id=org.rideflow'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/us/app/rideflow-riders/id6759728442'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

Rideflow Riders is the driver side of the Rideflow logistics platform. Independent riders and riders working for logistics companies go online, accept or decline delivery requests, navigate to pickup and drop-off, and get paid, all with real-time updates between the rider, the customer and the dispatcher.

## Earn more on every delivery with faster order assignments.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rideflow_rider_demo.gif" width="250" />
        <br/><sub>Demo (<a href="assets/rideflow_rider/rideflow_rider_demo.mp4">MP4</a>)</sub>
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_home.png" width="250" />
        <br/><sub>Online dashboard</sub>
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_streak_sheet.png" width="250" />
        <br/><sub>Streak nudge on going offline</sub>
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_streak.png" width="250" />
        <br/><sub>Streaks & rewards</sub>
      </td>
    </tr>
  </table>
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_1.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_2.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_3.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_4.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/rideflow_rider/rider_5.png" width="600" />
      </td>
    </tr>
  </table>
</div>

## Key Features

1.  Real-Time Order Assignment:

        - Riders go online or offline with one switch and receive new delivery requests instantly over WebSockets (Socket.IO), with sound alerts, so they can accept or decline before the request moves on.

2.  Live Delivery Tracking:

        - Location updates with Geolocator stream the rider's position to the customer, and Google Maps guides the rider from pickup to drop-off with one-tap calls to the vendor and the customer.

3.  Independent Riders & Company Fleets:

        - Separate onboarding and home screens for independent riders and for riders managed by a logistics company, including dispatch from the company and document (KYC) verification.

4.  Wallet, Earnings & Streaks:

        - Riders track completed deliveries, earnings and wallet balance, and stay motivated with streaks: daily online-time goals and weekly ride targets that unlock cash rewards, with a nudge when they try to go offline early.

5.  In-App Support:

        - Live chat support with Tawk.to and push notifications for every status change.

6.  Code Quality at Scale:

        - Built a custom lint plugin that enforces the team's conventions in the IDE, git hooks that format and check code before push, and a required CI "Code Quality" check on every pull request.

## Tools

- Flutter/Dart 💙
- Riverpod for State Management 🚀
- GoRouter for Navigation 🧭
- Socket.IO (WebSockets) 🔌
- Google Maps & Geolocator 🗺️📍
- Firebase (Messaging, Crashlytics, Analytics) 🔥
- Local Notifications & Audio Alerts 🔔
- Custom Lint Rules & GitHub Actions CI ✅
- Shorebird (over-the-air updates) 🐦
- Optimized for iOS and Android 📱
  <br/>

#

# 3. Kamux Phone

Kamux Phone is a cross-platform business softphone built in Flutter for a German company moving its phone system to MikoPBX. Agents answer and make calls from their phone or desktop, see which colleagues are free in real time, and work from a shared history of every call that came into the central queue, so no missed caller is forgotten.

## (Demo)

<p align="left">
  <img src="assets/kamux_phone/kamux_phone_demo.gif" width="300" alt="Kamux Phone demo" />
</p>

[▶️ Watch the demo video (MP4)](assets/kamux_phone/kamux_phone_demo.mp4)

## Every call in the queue, every colleague's status, one app.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/kamux_phone/kamux_queue.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_phone/kamux_team.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_phone/kamux_call.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_phone/kamux_keypad.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_phone/kamux_menu.png" width="600" />
      </td>
    </tr>
  </table>
</div>

## Key Features

1.  Central Queue History:

        - A shared history of every call into the company's queue, with the caller's number and city, who answered it and for how long, and missed calls marked in red until someone calls back. Callers waiting right now can be picked up with one tap, and the list filters by All, Missed, Answered or Mine.

2.  Live Team Presence:

        - Every extension shows whether the colleague is available, ringing, on a call (with a live timer), on do-not-disturb or offline, and can be called with one tap.

3.  Full SIP Calling with Linphone:

        - Outgoing and incoming calls, mute, hold, speaker, DTMF keypad and call transfer, powered by the Linphone SDK through a custom Flutter plugin (Swift for iOS and macOS, Kotlin for Android).

4.  Native Incoming Calls on iPhone:

        - CallKit integration and a Flexisip push gateway, so calls ring on the lock screen like a normal phone call even when the app is closed.

5.  Nextcloud Contacts & Chat:

        - Contacts are synced from the company's Nextcloud address book over CardDAV, and the menu links straight to Nextcloud Talk for team chat.

6.  One Codebase for Mobile and Desktop:

        - Runs on iOS, Android, macOS and Linux, in English and German, with SIP credentials and PBX tokens kept in the OS keychain.

## Tools

- Flutter/Dart 💙
- Linphone SDK (SIP / VoIP) via a custom platform plugin 📞
- Swift (iOS & macOS) and Kotlin (Android) 🧩
- CallKit & Flexisip push gateway 🔔
- MikoPBX REST API with Dio 🌐
- CardDAV (Nextcloud) contacts 📇
- Riverpod for State Management 🚀
- GoRouter for Navigation 🧭
- Flutter Secure Storage 🔐
- Localization (en & de) 🌍
- GitHub Actions (Linux packages, push gateway deploy) ⚙️
- Optimized for iOS, Android & Desktop 📱💻
  <br/>

#

# 4. Captured Clean

Captured Clean is my own storage cleaner for Mac and iPhone. On the Mac it shows where your disk space went, finds caches, developer build data and old installers that are safe to remove, uninstalls apps with their leftovers, and monitors CPU and memory from the menu bar. On iPhone it finds duplicate photos, similar shots, large videos and big files. Nothing is deleted until you review it, and everything is scanned on the device.

🌐 [capturedclean.com](https://capturedclean.com) · 💻 [Download for Mac](https://download.capturedclean.com/Captured-Clean-1.1.dmg)

## (Demo)

<p align="left">
  <img src="assets/captured_clean/captured_clean_iphone_demo.gif" width="300" alt="Captured Clean iPhone demo" />
</p>

[▶️ Watch the iPhone demo (MP4)](assets/captured_clean/captured_clean_iphone_demo.mp4) · [▶️ Watch the Mac demo (MP4)](assets/captured_clean/captured_clean_mac_demo.mp4)

## A little breathing room for your iPhone and Mac.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_overview.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_duplicates.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_similar.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_files.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_widgets.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_settings.jpg" width="600" />
      </td>
    </tr>
  </table>
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_mac_overview.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_mac_cleanup.jpg" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/captured_clean/cc_mac_activity.jpg" width="600" />
      </td>
    </tr>
  </table>
</div>

## Key Features

1.  Photo Cleanup on iPhone:

        - Finds exact duplicate photos and near-identical shots, keeps the best one of each group, and lists screenshots and large videos biggest first. Deleted photos go to Recently Deleted for 30 days.

2.  Where the Space Went (Mac):

        - A size-aware file explorer that scans folders in parallel and sorts everything largest first, with on-disk sizes that match Finder, hard links counted once and symbolic-link loops handled safely.

3.  Safe Cleanup Suggestions:

        - Application caches and logs, Xcode build data and simulator caches, npm, Gradle, Cargo, Go, pnpm, Bun and Flutter caches, and old installers in Downloads. Nothing is selected automatically, and items go to the Trash only after you review them.

4.  App Uninstaller & Activity Monitor:

        - Removes an app together with its caches, preferences and other leftovers, and shows live CPU and memory per app with Quit and Force Quit.

5.  Menu Bar, Widgets & Storage Alerts:

        - The Mac app stays in the menu bar showing free space, the iPhone has home-screen widgets, and both can alert you when storage runs low.

6.  One Purchase, Mac and iPhone:

        - A free tier with monthly limits and a one-time Pro purchase, through the App Store on iPhone or a license key from the website that unlocks any mix of Macs and iPhones.

## Tools

- Swift 6 & SwiftUI 🧡
- AppKit (Mac) & UIKit (iPhone) 🍎
- PhotoKit (duplicate and similar photo detection) 🖼️
- WidgetKit (home-screen widgets) 🧩
- Swift Charts 📊
- RevenueCat (in-app purchases) & Sign in with Apple 🔐
- Cloudflare Workers (license keys, checkout, updates) ☁️
- Sparkle (Mac auto-updates) & Developer ID notarization ✍️
- PostHog analytics & Sentry crash reporting 📈
- Local Notifications 🔔
- Optimized for macOS and iOS 💻📱
  <br/>

#

# 5. Kamux PDF (Weasy)

Kamux PDF is a local-first Flutter desktop app for creating, storing and sending business documents as PDFs. Staff pick a template, fill in the customer's details, and the app renders a print-ready A4 PDF on their own computer, saves it into the company's synced Nextcloud folder, and can send formal letters straight to a postal delivery service over SFTP. There is no server: everything renders offline on the machine.

## Templates in, print-ready PDFs out.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center" colspan="2">
        <img src="assets/kamux_weasy/kamux_weasy_demo.gif" width="800" />
        <br/><sub>Combining two letter templates and rendering a live preview (<a href="assets/kamux_weasy/kamux_weasy_demo.mp4">MP4</a>)</sub>
      </td>
    </tr>
    <tr>
      <td style="text-align: center">
        <img src="assets/kamux_weasy/weasy_new_document.png" width="400" />
        <br/><sub>New document with a DIN 5008 letter preview</sub>
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_weasy/weasy_templates.png" width="400" />
        <br/><sub>Template library with detected mail-merge variables</sub>
      </td>
    </tr>
    <tr>
      <td style="text-align: center">
        <img src="assets/kamux_weasy/weasy_invoice_pdf.png" width="400" />
        <br/><sub>Invoice rendered with WeasyPrint</sub>
      </td>
      <td style="text-align: center">
        <img src="assets/kamux_weasy/weasy_report_pdf.png" width="400" />
        <br/><sub>Report with a JavaScript chart rendered with Chromium</sub>
      </td>
    </tr>
  </table>
</div>

<sub>The sample PDFs use placeholder data.</sub>

## Key Features

1.  Three Rendering Engines, Picked Automatically:

        - Static HTML and print CSS (invoices, reports) render with WeasyPrint, templates with JavaScript, charts or CSS grid render in Chromium through Playwright, and formal postal letters render from LaTeX with Tectonic. A job can also force one engine or allow a fallback.

2.  Flutter + Python Companion Architecture:

        - The Flutter desktop app talks to a bundled local Python engine through JSON job files, so the UI and the renderers stay separate processes and each operating system ships its own native engine.

3.  Document Workflow:

        - Documents move through Drafts, PDF ready and Sent, with search, a template library, a document editor, customer folders and a protocol log of everything generated.

4.  Nextcloud Storage & Postal Delivery:

        - Finished PDFs are written atomically into the locally synced Nextcloud folder of each customer, and letters can be submitted to a postal mailing service over SFTP.

5.  Print-Ready Output:

        - Every PDF is checked to be A4, with optional company letterhead (business paper) layered onto the first page or every page.

6.  Mail Merge for Many Recipients:

        - Pick one or more templates, drag them into order, choose recipients from a customer's recipient list, and the app fills each template's variables (salutation, name, street, postcode, city) to build one combined, DIN 5008-ready PDF per recipient. The UI is available in English and German.

7.  Private by Design:

        - No hosted server, open port, cloud database or Docker runtime. Job history lives in a local SQLite database outside the synced folder, and credentials are kept in secure storage.

## Tools

- Flutter/Dart (macOS, Windows, Linux desktop) 💙
- Riverpod for State Management 🚀
- Python companion engine (packaged with PyInstaller) 🐍
- WeasyPrint (HTML/CSS to PDF) 📄
- Chromium via Playwright (JavaScript & charts) 🌐
- LaTeX with Tectonic (postal letters) ✉️
- Nextcloud sync folder & SFTP delivery ☁️
- SQLite job history 🗂️
- Hive, Shared Preferences & Flutter Secure Storage 💾
- Optimized for macOS, Windows and Linux 💻
  <br/>

#

# 6. ArewaCare <a href='https://play.google.com/store/apps/details?id=com.arewa.arewa_pregnancy_app'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/ar/app/arewacare/id6745699860'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

AREWA Care helps women who are pregnant, trying to conceive, or seeking reliable pregnancy knowledge. Track symptoms and cycles, document how you feel, and stay informed with trusted insights in your preferred language

## (Intro-Video)


https://github.com/user-attachments/assets/92b52b57-9efb-4156-8da4-a80e79704df5


## Transforming healthcare management with innovative solutions

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/arewa_health/home_screen.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/arewa_health/guide_screen.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/arewa_health/Ipd_screen.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/arewa_health/Pregnancy_screen.png" width="600" />
      </td>
    </tr> 
  </table>
</div>

## Key Features

1.  Menstrual Cycle Tracking:

        - Comprehensive tracking system that monitors menstrual cycles with calendar visualization, allowing users to log symptoms, flow intensity, and related health data for accurate pattern recognition.

2.  Predictive Health Insights:

        - Advanced algorithms provide personalized predictions for fertile windows and ovulation periods, empowering users with accurate timing for conception planning and reproductive health awareness.

3.  Pregnancy Tools & Monitoring:

        - Complete pregnancy companion featuring week-by-week development tracking, symptom logging, appointment reminders, and essential pregnancy information to support users throughout their journey.

4.  Detailed Health Logs & Analytics:

        - In-depth health documentation system with visual analytics and trends, enabling users to track patterns, generate reports, and gain valuable insights into their reproductive and overall health.

5.  Multi-Language Support:

        - Accessible interface supporting multiple languages to serve a diverse user base, ensuring that women from different linguistic backgrounds can access vital health information in their preferred language.

6.  Clean Architecture & Optimized Performance:

        - Built with clean architecture principles and Riverpod state management for scalability, reliability, and smooth performance with micro-animations that enhance user experience and engagement.

## Tools

- Flutter/Dart 💙
- Firebase (firestore, storage, authentication) 🔥
- Clean Architecture 🏛️
- Riverpod for State Management 🚀
- Local Notifications 📬
- Multi-language Support (i18n) 🌍
- Shared Preferences 💾
- Custom Animations 🎨
- Optimized for iOS and Android 📱
- FHIR: Fast HealthCare Interoperabilityb resources
  <br/>

#

# 7. Verido <a href='https://play.google.com/store/apps/details?id=app.verido.app'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/ar/app/verido/id1598637042'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

Verido is a smart pricing and inventory management tool that automatically calculates profitable selling prices, tracks complete product costs to prevent losses, monitors discounts to protect profit margins, and identifies best-selling items to help businesses focus on their most profitable products and services.

## (Intro-Video)


https://github.com/user-attachments/assets/28947147-2df7-4c7a-90ee-4b716554ff53


## Making sure your business is profitable through smart management tools.

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/verido/market_place.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/verido/operations_page.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/verido/vendor_list.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/verido/admin_home.png" width="600" />
      </td>
    </tr> 
  </table>
</div>

## Key Features

1.  Offline-First Architecture:

        - Implemented a robust offline-first approach that prioritizes local data operations, ensuring the app remains fully functional without internet connectivity and seamlessly syncs when online.

2.  Local Data Caching with Hive:

        - Integrated Hive database for efficient local storage, enabling lightning-fast data retrieval, reduced network dependency, and persistent offline functionality for uninterrupted user experience.

3.  Manual Data Synchronization:

        - Developed a reliable synchronization system that manages data flow between local storage and remote database, ensuring data consistency and integrity across devices while minimizing conflicts.

4.  Clean Architecture Refactoring:

        - Restructured the entire codebase following clean architecture principles, resulting in clear separation of concerns, improved code modularity, enhanced maintainability, and better scalability for future growth.

5.  Optimized Performance:

        - Achieved significant performance improvements through efficient data caching, reduced network calls, and streamlined data access patterns, delivering faster load times and smoother user interactions.

6.  App Store Deployment & Management:

        - Responsible for the complete deployment pipeline including building production-ready apps, signing with appropriate certificates, and publishing to both Apple App Store and Google Play Store.

## Tools

- Flutter/Dart 💙
- Hive (Local Database) 📦
- REST API & Remote Database 🌐
- Clean Architecture 🏛️
- Riverpod & Provider for State Management 🚀
- Offline-First Sync Strategy 🔄
- Shared Preferences 💾
- Local data with HIVE
- App Store Deployment (iOS & Android) 🚀📱
- Optimized for iOS and Android 📱 <br/>

#

# 8. Soloride

<!-- <a href='https://play.google.com/store/apps/details?id=com.capturedHeart.eyeDr'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> -->

To revolutionize transportation in Nigeria by creating a ride-hailing platform that prioritizes affordability, safety, and community, while empowering drivers and providing seamless experiences for passengers.

## (Intro-Video)


https://github.com/user-attachments/assets/903c83b2-7155-464c-bdf7-7db3bbc19280


## Drive with Soloride: Earn more, stress less !!!

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_home.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_price.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_preferences.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/Soloride/soloride_referrals.png" width="600" />
      </td>
    </tr> 
     <tr>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_home2.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_trip_history.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/Soloride/soloride_music.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/Soloride/soloride_support.png" width="600" />
      </td>
    </tr>   
  </table>
</div>

## Key Features

1.  Functional Google Map:

        - The map is designed to display polylines for showing routes between the rider's and driver's locations. This ensures that both the rider and driver can track the path clearly and navigate smoothly.

        - Dynamic Map Themes: The app offers dynamic themes that adjust the appearance of the map based on the app's state.

2.  Seamless Voice Calls:

        - The in-app calling system provides users with an uninterrupted experience while communicating. Whether it’s for confirming pick-up points or clarifying trip details, both riders and drivers can make calls effortlessly.

3.  Saved Routes:

        - Riders and drivers can save common destinations and this eliminates the need to manually input these addresses each time.

4.  Trip Histories :

        - The app offers the ability to view detailed trip histories, allowing riders and drivers to track past rides and review the trip details.

## Tools

- Flutter/Dart 💙
- Firebase (firestore, storage) 🔥
- Cloud Notifications 🌩️
- Shared Preferences 💾
- Calls (with Agora SDK) 🤙
- Google Maps (polylines, markers, real-time) 🗺️📍
- Riverpod for State Management 🚀
- Websocket 🔌
- Optimized for iOS and Android 📱 <br/>

#

# 9. GovDrive <a href='https://play.google.com/store/apps/details?id=ng.com.galaxybackbone.drive'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a>

GovDrive is a secure and user-friendly document management solution designed for government ministries, departments, and agencies. It streamlines the storage, tracking, sharing, and collaboration of official documents, improving efficiency and productivity across public sector operations.

## (Intro-Video)


https://github.com/user-attachments/assets/f7d5ef43-9d92-447d-9ee1-a3fa5d1aca97


## Never Lose a File Again. Secure Your Documents with 1Gov Drive

<div style="text-align: center">
  <table>
    <tr>
     <td style="text-align: center">
        <img src="assets/1gov/1gov_auth.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/1gov/1gov_drawer.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/1gov/1gov_file_options.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/1gov/1gov_pdf.png" width="600" />
      </td>
    </tr>  
  </table>
</div>

## Key Features

1.  View, Share, Copy, and Send Files:

        -The app offers robust functionality for managing files in different formats, allowing users to interact with them in several ways.

2.  Sign Documents:

        - The app includes a document signing feature that allows users to sign documents electronically.

3.  Universal Document Viewers:

        - Whether the user is dealing with PDFs, Word, Excel, PowerPoint, image files, or even more specialized formats, the app can open and display them properly. This feature ensures that users can handle a diverse array of documents without needing multiple apps

4.  Search Functionalities:

        - The search functionality in the app allows users to quickly find specific documents or content within folders.

## Tools

- Flutter/Dart 💙
- REST API 🌩️
- Shared Preferences 💾
- Document Viewer 📑
- Riverpod for State Management 🚀
- Optimized for iOS and Android 📱

#

# 10. Eye-Dr <a href='https://play.google.com/store/apps/details?id=com.capturedHeart.eyeDr'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a>

EYE-DR is a groundbreaking mobile application designed to enhance the screening and management of diabetic retinopathy (DR). Tailored for healthcare professionals and individuals with diabetes, EYE-DR leverages advanced technology to provide a seamless, efficient, and accurate solution for retinal imaging and DR detection.

## (Intro-Video)

https://github.com/user-attachments/assets/ffbe90d8-951f-40c9-a622-776e3f658a7b

## Eye-Dr: Screening and management of diabetic retinopathy (DR)

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/eye_dr/eye_dr_1.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/eye_dr/eye_dr_2.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/eye_dr/eye_dr_3.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/eye_dr/eye_dr_4.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/eye_dr/eye_dr_5.png" width="600" />
      </td>
    </tr>   
  </table>
</div>

## Key Features

1.  Intuitive and user-friendly interface:

        - Easily enter patient details, capture images, and view results with our intuitive app.

        - Light and dark modes

2.  Portable Imaging:

        - Attach a portable ophthalmoscope to your smartphone for high-quality retinal images anytime, anywhere.

3.  AI-Powered Analysis:

        - Leverage our cutting-edge deep learning model for accurate DR detection and grading.

4.  Comprehensive Reports :

        - Get detailed diagnostic reports with actionable insights. Cross-Platform Availability: Available on both iOS and Android.

## Tools

- Flutter/Dart 💙
- Firebase (firestore, auth, storage) 🔥
- Shared Preferences 💾
- Lottie 🐠
- Localization (en & my) 🌎
- Tensorflow 🗂️
- Firebase Machine Learning ⚙️
- Riverpod for State Management 🚀
- Themes (Light🌕 and dark 🌒)
- Optimized for iOS and Android 📱

<!---------------------- KOCHURE   -------------------------->
<br/>

#

# 11. AssetWize <a href='https://play.google.com/store/apps/details?id=com.assetwize.app'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/us/app/assetwize/id6740449088'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

This secure file management app focuses on protecting sensitive user information, such as insurance documents, land titles, jewelry receipts, and other valuable assets, by encrypting and storing them securely on the user's phone. Additionally, the app offers an optional backup feature to sync the files with the user’s cloud or drive for extra security and accessibility.

## (Intro-Video)


https://github.com/user-attachments/assets/44548d57-05be-4267-b905-693c2e276b72


## Encrypted and secured documents

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/assetWise/assetwise_home.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/assetWise/assetwise_home2.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/assetWise/assetwise_docs.png" width="600" />
      </td>
       <td style="text-align: center">
        <img src="assets/assetWise/assetwise_insurance.png" width="600" />
      </td>
    </tr> 
    
  </table>
</div>

## Key Features

1.  Encrypted Document Storage:

        - All user documents, such as insurance policies, land deeds, jewelry receipts, and other critical assets, are encrypted using industry-standard encryption algorithms(AES-256). This ensures that sensitive information is protected from unauthorized access, even if the device is lost or compromised.

2.  Offline-Support:

        - Users can store and access their important documents directly on their phones, with everything kept within the app for ease of use even without the Internet-enabled on the device.

3.  Cloud Backup:

        - The app allows users to create encrypted backups of their documents in the cloud, ensuring that files are stored securely off-device.

        - Users can set automatic or manual backup intervals, giving them control over when and how their documents are backed up.

4.  Intuitive and user-friendly interface:

        - Users can create custom categories or folders (e.g., “Insurance,” “Land Titles,” “Jewelry Receipts”) to organize their documents based on asset type. This allows them to quickly find specific documents when needed.

## Tools

- Flutter/Dart 💙
- Firebase (Authentication) 🔥
- Cloud Backup (Google Drive & iCloud) 🌩️
- Shared Preferences 💾
- Encryption and Decryption 🔐
- PDF Previewer 📄
- PDF password removal 🔑
- Riverpod for State Management 🚀
- Optimized for iOS and Android 📱 <br/>

#

# 12. Kochure <a href='https://play.google.com/store/apps/details?id=com.kochure.kochureApp'><img alt='Download on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/us/app/kochure-buy-and-sell-crypto/id1595574962'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

Easily convert your cryptocurrencies to cash in Nigeria at the lowest fees. Pay the lowest transaction fee of 1.99% on every transaction and begin your crypto journey with as little as N500.

## (Intro-Video)

https://github.com/user-attachments/assets/e85cf921-20df-4fb3-98a3-9e96f8987566

## Kochure: hold, buy, sell, save, receive cryptocurrencies

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/kochure/kochure_1.png" width="800"/>
      </td>
      <td style="text-align: center">
        <img src="assets/kochure/kochure_2.png" width="800"/>
      </td>
      <td style="text-align: center">
        <img src="assets/kochure/kochure_3.png" width="800"/>
      </td>
       <td style="text-align: center">
        <img src="assets/kochure/kochure_4.png" width="800" />
      </td>
      <td style="text-align: center">
        <img src="assets/kochure/kochure_5.png" width="800" />
      </td>
    </tr>
  </table>
</div>

## Key Features

1.  Intuitive and user-friendly interface:

        - Enjoy a sleek and intuitive user interface designed for seamless navigation and effortless interaction.

        - Light and dark modes

2.  Real-time candlestick chart;

        - Find your winning trade at a glance by analyzing the crypto market with your mobile device.

3.  Price alert notification:

        - Never miss a trade! Get an instant notification on your phone when the price of a crypto token or coin reaches a particular price you set.

4.  Multi-level Authentication:

        - The Kochure app is built with the latest blockchain security features with military-grade encryption, your crypto assets are safe and can only be assessed by you.

5.  Multi-coin feature:

        - Buy, sell, swap, and HODL over 40 coins and tokens on the Kochure app.

6.  Savings:

        - Unlock the power of this feature and watch your savings thrive with up to 12% interest. With options to top-up and withdraw at any time (Flexible)

## Tools:

- Themes (Light🌕 and dark 🌒)
- NodeJs (Login/Sign up, Reset Password, biometric)
- Binance API - Push Notification (Firebase Messaging🔥)
- QR-code generator and scan for wallet address and payment 攀
- Provider for State Management 🚀

#

# 13. Connect-Me <a href='https://apps.apple.com/ng/app/connect-me-digital-identity/id6478838388'><img alt='Download on the App Store' src='./assets/app_store.png' height='23px'/></a> <a href='https://play.google.com/store/apps/details?id=com.capturedHeart.connectMe'><img alt='Get it on Google Play' src='./assets/google_play.png' height='23px'/></a>

<strong> Connect_Me is a user-friendly mobile application that empowers users to streamline their communication, networking, and information-sharing processes with the power of QR codes. Whether you're a professional seeking to exchange business details, a social media enthusiast connecting with new friends, or a tech-savvy individual looking for a convenient way to share information, Connect_Me is the ultimate solution for all your QR code needs. </strong>

<br/>

## (Intro-Video)

https://github.com/Captured-Heart/connect_me/assets/69226443/63c2abe0-4c5f-4151-9f9a-77beb289a4b7

## Connect-Me: QR code Digital ID

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="./assets/connect_me/home.PNG" width="800" />
      </td>
      <td style="text-align: center">
        <img src="./assets/connect_me/profile.PNG" width="800" />
      </td>
       <td style="text-align: center">
        <img src="./assets/connect_me/connect_dark2.PNG" width="800" />
      </td>
      <td style="text-align: center">
        <img src="./assets/connect_me/share1.PNG" width="800" />
      </td>
       <td style="text-align: center">
        <img src="./assets/connect_me/themes.PNG" width="800" />
      </td>
    </tr>
    <tr>
       <td style="text-align: center">
        <img src="./assets/connect_me/home_light.PNG" width="800" />
      </td>
      <td style="text-align: center">
        <img src="./assets/connect_me/profile2.PNG" width="800" />
      </td>
      <td style="text-align: center">
        <img src="./assets/connect_me/connect_light.PNG" width="800" />
      </td>
      <td style="text-align: center">
        <img src="./assets/connect_me/share_light.PNG" width="800" />
      </td>
       <td style="text-align: center">
        <img src="./assets/connect_me/themes2.PNG" width="800" />
      </td>
    </tr> 
  </table>
</div>

## Key Features

1.  QR Code Generator:

         - Easily create custom QR codes for various purposes such as sharing contact details, website URLs, social media profiles, work experience, and more.

2.  QR Code Scanner:

         - Seamlessly scan QR codes using your device's camera and also via QR code images

3.  Personal Information Profile:

        - Create, update, and save your personal information profile within the app, including contact details, social media links, bio, and profile picture.

        - Attach your personal information profile to a custom QR code, allowing you to share comprehensive details with others in a single scan.

4.  Add Users via QR Codes:

          - Easily add new contacts to your network or exchange information with colleagues, friends, or business partners by scanning their QR codes.

5.  User-Friendly Interface:

         - Enjoy a sleek and intuitive user interface designed for seamless navigation and effortless interaction.

         - Light and dark modes

<!---------------------- HOMETOWN   -------------------------->
<br/>

#

# 14. Hometown <a href='https://play.google.com/store/apps/details?id=com.hometown.app'><img alt='Download hometown on the Play Store' src='./assets/google_play.png' height='23px' align="center"/></a> <a href='https://apps.apple.com/ng/app/hometown-banking-solution/id1525335534'><img alt='Download hometown on the App Store' src='./assets/app_store.png' height='23px' align="center"/></a>

Hometown is not just an app; it's your passport to financial bliss. Embrace banking freedom. Manage your finances from the comfort of your home, office, or while you're on the move - 24/7 accessibility guaranteed.

## (Intro-Video)

https://github.com/user-attachments/assets/4e570419-3292-40a0-b6a7-a01e754ff043

## Hometown: The Ultimate Banking Experience

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/hometown/hometown_1.png" width="800" />
      </td>
      <td style="text-align: center">
        <img src="assets/hometown/hometown_2.png" width="800" />
      </td>
      <td style="text-align: center">
        <img src="assets/hometown/hometown_3.png" width="800"/>
      </td>
       <td style="text-align: center">
        <img src="assets/hometown/hometown_4.png" width="800" />
      </td>
      <td style="text-align: center">
        <img src="assets/hometown/hometown_7.png" width="800"  />
      </td>
    </tr>
  </table>
</div>

## Application Features:

1.  Transactions Made Simple:

        - Sending and receiving money has never been easier. With Hometown, transfer funds to any Nigerian account effortlessly, and witness the magic of swift transactions.

2.  Pay with Ease:

        - Why wait another minute? Settle essential services like DSTV, GoTV, Startimes, Showmax, PHCN subscriptions, and more in seconds right from the Hometown app.

3.  Grow Your Savings:

        - Unlock the power of the Akawo feature and watch your savings thrive with up to 12% interest. You can sleep soundly knowing your money is working tirelessly to secure your future.

4.  Get Instant Loans:

        - You are not alone. Let's help you ease the financial burdens. Get asses to the lowest-interest loans at the click of a button.

5.  Book Your Next Flight

        - Flying to any destination now begins from home. Book your next local or international flight easily and at the best price with the Hometown.

#

<h1 align="center">📝 BLOG POSTS</h1>

<p align="center">Sharing knowledge and insights from my Flutter development journey</p>

<br/>

## Featured Articles

### 1. 🌍 Flutter meets Igbo: Integrate Igbo and Other Native Languages into Flutter Apps

A comprehensive step-by-step guide on implementing native language support in Flutter applications using the `easy_localization` package. Learn how to make your apps accessible to diverse linguistic audiences.

**[Read the full article →](https://capturedheart.hashnode.dev/flutter-meets-igbo)**

<br/>

### 2. 🗺️ Enhance Your Google Maps with Dynamic Themes Using Riverpod

Discover how to implement dynamic theming for Google Maps in your Flutter applications using Riverpod state management. Create seamless light and dark mode transitions for better user experience.

**[Read the full article →](https://capturedheart.hashnode.dev/enhance-your-google-maps-with-dynamic-themes-using-riverpod)**

<br/>

#

<h1 align="center">🔌 FLUTTER PLUGINS</h1>

<p align="center">Open-source contributions to the Flutter ecosystem</p>

<br/>

## Published Packages

### 1. 🗺️ map_themes

A Flutter plugin that provides easy-to-use map theming capabilities for Google Maps and other map implementations. Transform your maps with beautiful predefined themes or create custom styling with minimal code.

**Key Features:**
- 🎨 Pre-built theme collections (dark, light, custom)
- ⚡ Simple API for quick implementation
- 🔧 Highly customizable styling options
- 📱 Cross-platform support (iOS & Android)

**[View on pub.dev →](https://pub.dev/packages/map_themes)**

<br/>

#

<p>
<h1 align="center"> ANIMATIONS</h1>
</p>

<div style="display: flex; flex-direction: column; height: 100vh; justify-content: space-between;">
    <div style="display: flex; width: 100%;">
        <div style="flex: 1; padding: 20px; box-sizing: border-box;">
            <!-- Left content here -->
          <h2>Moniepoint Assessment  <a href='https://drive.google.com/drive/folders/19rPMzMpCHUe5Tllrf6ZFekBKlLw468Sh?usp=drive_link'><img alt='Download moniepoint apks on the Google drive' src='./assets/google_drive.png' height='20px' align="center"/></a> 
  <a href='https://github.com/Captured-Heart/moniepoint_assessment_marcel'><img alt='see repository on Github' src='./assets/github.png' height='20px' align="center"/></a> </h2> 
    <h4> AN INTRO VIDEO OF THE APP </h4>
  
  https://github.com/Captured-Heart/moniepoint_assessment_marcel/assets/69226443/d33b1af3-3300-4695-bb76-5b8aa1fd36f8

## UI Shots

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/moniepoint/home.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/moniepoint/maps.png" width="600" />
      </td>
    </tr>
  </table>
</div>

## Tools

- [google_maps_flutter](https://pub.dev/packages/google_sign_in): A Flutter plugin that provides a Google Maps widget.
- [SVG_Repo](https://www.svgrepo.com/vectors/shield/): Free Shield SVG Vectors and Icons. Shield icons and vector packs for Sketch, Figma, websites, or apps. Browse 50 vector icons about the Shield term.
- [animated_flip_counter](https://pub.dev/packages/animated_flip_counter): An implicit animation widget that flips from one number to another.
- [auto_size_text](https://pub.dev/packages/auto_size_text): Flutter widget that automatically resizes text to fit perfectly within its bounds.
- [flutter_animate](https://pub.dev/packages/flutter_animate): A performant library that makes it simple to add almost any kind of animated effect in Flutter.
- [flutter_svg](https://pub.dev/packages/flutter_svg): Draw SVG files using Flutter.

</div>
<div style="width: 0.3px; background-color: #ffffff;"></div>
<div style="flex: 1; padding: 20px; box-sizing: border-box;">
<!-- Right content here -->
<h2>Animated Button <a href='https://drive.google.com/drive/u/0/folders/1JiqyjuY2ybc49v5xv7TmqjdiujqdHEgB'><img alt='Download animated apks on the Google drive' src='./assets/google_drive.png' height='20px' align="center"/></a>
<a href='https://github.com/Captured-Heart/animated_button_progress'><img alt='see repository on Github' src='./assets/github.png' height='20px' align="center"/></a> </h2>
    <h4> AN INTRO VIDEO OF THE APP </h4>
      
  https://github.com/Captured-Heart/animated_button_progress/assets/69226443/cea90a04-4a75-45cb-9db7-f15eb54e0408

## UI Shots

<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="assets/animated/web.png" width="600" />
      </td>
      <td style="text-align: center">
        <img src="assets/animated/mobile.png" width="600" />
      </td>
    </tr>
  </table>
</div>

## Tools

- [gusto_neumorphic](https://pub.dev/packages/gusto_neumorphic): A complete, ready to use, Neumorphic ui kit for Flutter.
- [auto_size_text](https://pub.dev/packages/auto_size_text): Flutter widget that automatically resizes text to fit perfectly within its bounds.

</div>
</div>
