# Frenlock for Android

Frenlock is a mobile app where friends hold the brake. Lock a memecoin position in your own vault on Solana
and pick 1–3 friends: anything big waits for them, or for time. They never touch your money.
More at [frenlock.fun](https://frenlock.fun).

This repository hosts the Android builds of the open beta, which runs on Solana devnet with test money. The
app's source is in a private repository during the hackathon.

## Install

1. On your Android phone (Android 7 or later), open [frenlock.fun/android](https://frenlock.fun/android). It
   downloads `frenlock.apk` from the [latest release](../../releases/latest).
2. Open the file and allow installs from your browser when Android asks.
3. Sign in with your email. The app creates your wallet, and Get test money fills it with devnet test tokens.

On a Xiaomi, Redmi or POCO phone, turn on Autostart for Frenlock (Settings → Apps → Permissions → Background
autostart), or a friend's request waits until you open the app. The app shows the way too.

Most updates reach the app over the air. A new release appears here when the app's native code changes;
install it over the old one and you stay signed in.

## Verify

Each release lists its APK's SHA-256. Every build is signed with the same release key, certificate SHA-256
`95:98:A9:84:CD:96:BC:BF:A4:6C:52:60:24:D6:2A:95:4A:F8:7A:3B:F9:44:32:D8:B1:DB:86:E1:77:6B:0F:EB`
(`apksigner verify --print-certs frenlock.apk`).

iPhone: the TestFlight beta at [frenlock.fun/ios](https://frenlock.fun/ios). Questions: support@frenlock.fun or
[@frenlockfun](https://x.com/frenlockfun).
