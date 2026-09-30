# JavaScript Foundations: Event Welcome Center

Practice JavaScript fundamentals by building a small event welcome program. The page is already connected to `script.js`, so you can focus on the code and see the results in your browser.

## Get Started

1. Open `index.html` in your browser.
2. Open the browser's developer tools and select **Console**.
3. Edit `script.js`, save, and refresh the page to run your changes.

Work through the challenges in order. The examples in `index.html` show the expected patterns.

## Challenges

1. **Event information:** Create values for the event name, speaker, room, and attendee. Log each value with `console.log()`.
2. **Personalized greetings:** Combine the attendee and event values into a welcome message. Log the room information too.
3. **Functions:** Put messages into `welcomeGuest()` and `displaySessionInfo()`, then call both functions.
4. **Alerts:** Add an `alert()` for each team member. The browser pauses at each alert until you dismiss it, so keep these messages short.
5. **Attendee counter:** Start `attendeeCount` at `0`, log it, increase it with `attendeeCount++`, and log the new total.

## Check Your Work

- Refresh the page and dismiss the alerts one at a time.
- Confirm the event details, greetings, function messages, and counter values appear in the Console.
- If you see `ReferenceError`, check that the variable is declared before it is used and that its spelling and capitalization match.
- If nothing appears, confirm `script.js` is saved and linked near the end of `index.html`.

## Stretch and Reflect

- Add a `displaySpeaker()` function or welcome several attendees with personalized messages.
- Try `console.table()` with event details.
- Think about what was easiest, what was confusing, and how an alert differs from a console message.
