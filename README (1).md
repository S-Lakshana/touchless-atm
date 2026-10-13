# Touchless ATM (phone version)

Touchless ATM using hand gestures. Runs in a phone or laptop browser with the front camera, built with MediaPipe Hands.

## Pipeline
Video capture -> frame preprocessing -> BlazePalm hand detection -> 21 hand landmarks -> Euclidean distance + EMA smoothing -> virtual ATM UI

## How to use
1. Open the page and tap **Start camera**, then allow camera access.
2. Show 1, 2 or 3 fingers to choose a language.
3. Enter the demo PIN `1234` by showing 1, 2, 3, 4 (hold each gesture steady for 24 frames).
4. Main menu: 1 Check balance, 2 Withdraw cash, 3 Exit.
5. Withdraw: 1-5 picks the amount, then 1 confirms and 2 cancels.

## Run it
Camera needs HTTPS, so host it on GitHub Pages: Settings -> Pages -> Deploy from branch `main` / root.
