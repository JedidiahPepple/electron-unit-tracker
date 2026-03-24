# electron-unit-tracker
A simple mobile first prepaid electricity unit tracker.

# Documentation

## What is this?

Electron Power Tracker is a simple web app that helps you manage your prepaid electricity better. Instead of guessing when your units will run out or how much to buy, you just type in your electric unit details and it tells you exactly what you need to know.
No internet connection required. No account. No complicated setup. Just open it and use it.

## Why was it made?

Of recent there was a week long power outage in my rented space because the prepaid meter switched off when it exhausted its units. We had to call officials to reactivate it. Moreover sudden power outages can be embarrassing and annoying so this application aims to solve that and helps you plan better on your units' purchase.

## What can it do?

There are two things the app helps you figure out:
1. How long will my units last?
You tell it:
How many units you currently have
How many units you use per day (on average)
The cost per unit in Naira (optional)

It tells you:
How many days your units will last
Whether your situation is Stable, Low, or Critical
How much you're spending per day (if you entered a cost)

2. How many units should I buy?
You tell it:
How many days you want your electricity to last
How many units you use per day
The cost per unit in Naira (optional)

It tells you:
Exactly how many units to buy
The total amount it will cost you
Your daily spend (if you entered a cost)

## How to use it

Step 1 — Open the app in your browser.

Step 2 — Pick a tab at the top depending on what you want to find out:

"How long will it last?" if you already have units and want to know how many days they'll cover
"How much should I buy?" if you want to plan ahead for a specific number of days

Step 3 — Fill in the fields. The cost per unit is optional, you can skip it if you just want to know the days or units without the money breakdown.

Step 4 — Hit Calculate. Your result will be generated.

Step 5 — Use the 🌗 Theme button to switch between dark and light mode, whichever is easier on your eyes.
Technical details (for the curious)
Built with plain HTML, CSS, and JavaScript , no frameworks or dependencies were used.

Runs entirely in the browser; nothing is sent to any server
Works offline once loaded

Mobile-friendly layout that fits any screen size
Dark mode and light mode supported

##### Calculations explained
How long will it last?
Days remaining = Units available ÷ Daily usage
Daily spend    = Daily usage × Cost per unit

##### How many units to buy?
Units to buy   = Target days × Daily usage
Total cost     = Units to buy × Cost per unit
Daily spend    = Daily usage × Cost per unit

### Possible future improvements

- Let users save their daily usage so they don't have to type it every time.
- Add a recharge history log.
- Send a reminder notification when units are running low.
- Supports other currencies apart from Naira.
- Directly recharge meter with provided meter number and a cash wallet feature to fund tokens.
- Auto recharge units when meter is predicted to be extremely low on units (only applicable if the setting is turned on).
- Export to app store as a standalone app.
