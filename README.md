# Baseball Player Classic

**Privacy Policy**

**Effective date:** 2026-09-21 · **Applies to:** version 2.0.0 and later

Baseball Player Classic ("the App") is made by Chen-Kuo Chou, an individual developer based in Australia. This policy explains what the App does with information. It replaces the policy that covered versions 1.0.0 and earlier, which described a different app.

## Summary

- There is **no account**. You never give the App a name, an email address or a password, and there is nothing to sign in to.
- Your collection, your currency and your progress are stored **on your device**, in a database file inside the App's own storage.
- A compressed copy of that save is kept in **your own iCloud**, using Apple's key-value storage, so that reinstalling the App does not lose what you paid for. That copy is in your Apple Account. The developer cannot read it.
- The App sends **anonymous, aggregated usage counts** to TelemetryDeck, an analytics service based in Germany. No name, no email, no advertising identifier, and nothing you have typed.
- The App does **not** show ads, does **not** use tracking as Apple defines it, and does **not** share anything with data brokers.
- Purchases are handled entirely by **Apple**. The developer never sees your payment details.

## 1. What is stored on your device

The App keeps one database file in its own storage containing: which cards you have pulled and how many copies of each, their levels, your coins, gems and shards, your lineup, which campaign stages you have cleared, each banner's guarantee counter, and a log of changes to your balances. This log exists so that a question like "where did my gems go?" has an answer.

This file is included in your device's normal iOS backup. Deleting the App deletes it.

## 2. What is stored in your iCloud

So that deleting and reinstalling the App does not destroy a collection you have paid for, the App writes a compressed copy of the save — normally under five kilobytes — to Apple's iCloud key-value storage under your own Apple Account. It contains the same game data described in section 1, minus the change log.

This is your iCloud, not a server belonging to the developer. Nothing about it reaches the developer, and there is no way for the developer to read it. You can switch iCloud off for the App in iOS Settings, and Settings ▸ Your save inside the App tells you whether a copy exists.

## 3. What is sent to the analytics service

The App uses [TelemetryDeck](https://telemetrydeck.com) so that the developer can tell whether the game is too hard, whether people finish the tutorial, and how the campaign is actually going. This is the complete list of what an event can contain:

| Event | What it carries |
|---|---|
| App launched | Whether this is a returning player |
| Tutorial step reached | The step's name |
| Tutorial finished | Whether it was skipped |
| Founder pack granted | Nothing |
| Cards pulled | The banner's name, how many cards, the best rarity, and whether it was the opening guaranteed pull |
| First Legendary | How many pulls it took |
| Battle finished | Stage number, won or lost, the margin, and your club's rating **as a five-point band** rather than the exact number |
| Shop opened | Whether you opened it yourself or ran out of gems |
| Purchase credited | Which gem pack, its US price tier, and whether it was a first purchase |

Every event also carries the App's version number and the standard device information TelemetryDeck collects: device model, operating system version, and locale.

TelemetryDeck identifies a player by a one-way hash of Apple's "identifier for vendor", computed on your device and salted again when it arrives. It is never sent as a readable identifier, and it cannot be used to contact you or to recognise you in any other app. The purchase event carries the gem pack's planned US price tier and not the amount you were charged, because a local currency is a rough indication of where you are and the App does not want one.

TelemetryDeck processes data in the European Union. Their privacy policy is at <https://telemetrydeck.com/privacy/>.

**You can turn all of this off.** Settings ▸ Privacy ▸ Share anonymous usage data. Switching it off stops new events and discards any that have not been sent yet.

## 4. Purchases

The App sells consumable gem packs. Purchases go through Apple's In-App Purchase system. Apple tells the App that a purchase succeeded and which product it was; the developer never receives your payment card, your Apple Account, your name or your address. Apple's own privacy policy covers the transaction.

The App records which product you bought and when, on your device, so that the first-purchase bonus is not paid twice and so that a purchase interrupted by a crash is delivered rather than lost.

## 5. Children

The App is not directed at children under 13 and does not knowingly collect personal information from anyone. There is no account, no profile, no chat, no user-generated content and no way for players to contact each other. The App does contain in-app purchases; if you are a parent, iOS Screen Time can turn those off.

## 6. Your choices

- **Turn off analytics** — Settings ▸ Privacy, inside the App.
- **Delete everything on the device** — Settings ▸ Reset everything on this device, inside the App. This is immediate and cannot be undone.
- **Remove the iCloud copy** — switch iCloud off for the App in iOS Settings, or delete the App.
- **Ask a question or make a request** — email the address below. Because there is no account, the developer has no way to look you up, which also means there is nothing about you to hand over or erase on request beyond what is described above.

## 7. Changes

If this policy changes, the new version is posted here and the effective date above is updated. Material changes will also be noted in the App's release notes.

## 8. Contact

**hello@chenkuochou.com**

---

*Baseball Player Classic is not affiliated with, endorsed by, or licensed by Major League Baseball or any of its clubs. Every player, club and city in the game is invented.*
