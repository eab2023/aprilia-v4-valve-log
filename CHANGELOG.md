# Changelog

## v3.0 (2026-09-17)

Got more than one bike? Each one now keeps its own readings, shim kit, service details, and history. Add a bike with the + button and switch between them with the dropdown. If you used v2, your existing log carries over on its own.

When you finish a job, tap "Save current & start new" under Service history. The finished service is kept with its date and mileage, so next time you can look back and see which valves have been moving.

Give a bike a check interval and the app will show roughly when the next check is due, based on your odometer.

There's a tools list now, behind the wrench icon at the top. It separates what you need for a quick clearance check from what you need to pull the cams and swap shims, with a checkbox for each item. OEM part numbers come from the service manual. Anything marked "guide" comes from Fostytou's valve write-up on ApriliaForum, including the homemade tool options. Thanks to him and Amauri for doing the legwork on that.

Smaller things:
- Specs show inches next to millimeters, and torques show lb·ft next to Nm.
- Export can copy straight to your clipboard or switch to CSV for a spreadsheet.
- Type something that looks off, like 2.5 when you meant 0.25, and you'll get a heads-up.
- Cleaner layout. The valve diagram sits right under the tally, and torque specs fold away until you need them.

## v2.0 — 2026-09-05

### New shim tracking — knows what came out AND what went in
v1 only recorded the old shim you pulled. v2 adds a "new shim" field so the
log shows both the shim removed and the shim installed, side by side, in
every export and printout. If you sell the bike, the next owner (or you, next
service) can see exactly what's in there now — not just what used to be.

### Try a shim size before you commit
Type any shim thickness into the new field and the sheet instantly shows the
gap you'd land at and whether that's in spec — before you drop it in the
engine. Works as a live "what if" calculator while you're picking through
your shim tray.

### Pick your shim kit — OEM or Hot Cams (AF1)
New toggle at the top of the sheet. OEM shims and the Hot Cams HCSHIM00 kit
that AF1 sells come in different sizes and different increments. Switch
kits and every suggested shim size updates to a size that actually exists in
that kit — no more math that points you at a size nobody sells.

### Torque specs, right on the sheet
Pulled straight from the 2016 Tuono V4 1100 RR/Factory service manual —
covers the actual fasteners you'll touch for this job: tank bolts, valve
cover, spark plugs, coils, the crank-turning inspection cap, cam towers, and
the cam timing gear screw (with the reminder that screw gets replaced every
time, straight from the manual).

### Service record fields
Date, mileage, VIN, model/year, who did the work, location, and notes.
Fill them in once and every export/printout carries them — turns a plain
number dump into an actual service record you can hand to a buyer or keep
for your own history.

### Print a blank sheet for the garage, or a filled one for the record
New "Print / PDF" button lays out the same cylinder/front-rear layout you see
on screen, ready to print. Print it blank and fill it out by hand at the
bike, or print your finished digital log as a clean, professional record —
your call.

### Light mode
Tap the sun/moon icon top-right. Useful in bright light or if the old
dark-only screen was hard to read in your garage.

### Easier to read, period
Bigger text, better color contrast, bolder labels — built for glancing at
mid-service with greasy hands, not squinting at 9pt gray text.

---

## v1.0 — initial release
Single-file valve clearance and shim calculator. Enter measured gap and old
shim thickness per valve, get a suggested shim change. Export a plain-text
log. Dark UI only, no service record fields, no kit selection.
