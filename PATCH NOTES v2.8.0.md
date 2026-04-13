# undercover00 — Patch Notes

---

## v2.8.0 — Tab Notification System
- Browser tab favicon now blinks when a new message arrives and the tab is inactive
- Favicon alternates between default icon and a red dot notification indicator
- Blinking stops immediately when the user returns to the tab
- Multiple incoming messages do not stack intervals
- Original favicon restored on tab focus

---

## v2.7.0 — Stability & UX Improvements
- Server region shifted from US East (Virginia, USA) to Southeast Asia (Singapore)
- Fixed email delivery issue by correcting recipient handling to ensure reliable notifications
- Updated system message from "Chat cleared." to "New session started." for improved session clarity
- Updated CMD boot screen text for improved realism and interface consistency
- Changed [ CLS ] Button to [ NWS ] for better abstraction
- Added project logo to browser's tab

---

## v2.6.0 — Timezone Localization
- Message timestamps now display in Indian Standard Time (IST, UTC +5:30)
- Applies to both incoming and outgoing messages
- Resolved incorrect GMT time display in CMD UI

---

## v2.5.0 — Two-Way Reply System
- Full reply support for both incoming and outgoing messages
- Every message now displays a unique local ID for reference
- To reply, type !r <id> your message or use the reply banner
- Outgoing replies sent as proper Discord replies on the friend's end
- Incoming replies show reply context line with original message preview
- Reply banner displays above input when a reply target is active
- Cancel reply option added to dismiss reply mode

---

## v2.4.0 — Notification Content Privacy
- Email notifications no longer expose sender identity or message content
- Notification delivered as a generic system alert
- Subject and body replaced with neutral placeholder content
- Improved discretion for sensitive communication environments

---

## v2.3.0 — Production Release
- Fully stable end-to-end system
- Real-time messaging, web control, and email alerts functioning together
- Clean session handling and reliable cloud deployment
- System approved for public use

---

## v2.2.0 — Stability & Bug Fixes
- Fixed connection issues between UI and backend
- Resolved session auto-disconnect bug
- Improved API communication reliability
- Ensured consistent message delivery and state synchronization

---

## v2.1.0 — Email Delivery Upgrade
- Replaced SMTP with API-based email delivery system
- Improved delivery reliability and performance
- Resolved network-related sending failures on cloud environments
- Enhanced compatibility with hosted infrastructure

---

## v2.0.0 — Smart Notification Control
- Email notifications now toggle intelligently based on session state
- Eliminated duplicate and unnecessary alert triggers
- Improved handling of active versus inactive user sessions

---

## v1.9.0 — Email Notification System
- Implemented email alerts for incoming messages during inactive sessions
- Added conditional logic to control notification triggers
- Improved notification formatting and delivery flow

---

## v1.8.0 — Stability & Deployment Fixes
- Fixed deployment issues on cloud environment
- Resolved runtime crashes caused by environment mismatches
- Improved startup reliability and system logging
- Optimized background execution flow

---

## v1.7.0 — Connection & Presence System
- Introduced connect and disconnect session handling
- Bot presence now synchronized with UI session state
- Fixed inconsistent connection behavior across sessions

---

## v1.6.0 — CMD Interface Support
- Connected CMD-style web interface to backend
- Enabled sending and receiving messages via browser UI
- Added session-based interaction flow
- Improved UI responsiveness and real-time updates

---

## v1.5.0 — Web Server Integration
- Integrated internal web server for real-time communication
- Enabled API endpoints for message fetch, send, and session control
- Established connection layer between bot and external UI
- Improved message logging structure

---

## v1.4.0 — Notifications & Status Indicator
- Bot status now reflects active session state
- Active session sets status to Online, closing session sets it to Invisible
- Email notification system added for away state
- Notifications only fire when no active session is detected

---

## v1.3.0 — Disconnect Notice
- App now sends an automatic disconnect notice when session ends
- Shutdown handled gracefully with no errors

---

## v1.2.0 — UI & UX Improvements
- Refresh rate improved from 4 seconds to 2 seconds
- Minor config screen improvements
- Button styling updated

---

## v1.1.0 — Clear Chat
- Added [ CLS ] button to clear the chat window
- Chat history wiped cleanly from both UI and memory
- No messages reload after clearing

---

## v1.0.0 — Initial Release
- Terminal-style chat interface built to look like Windows CMD
- Send and receive messages through a connected bot
- Messages appear in real time with auto-refresh
- One-click startup system included
