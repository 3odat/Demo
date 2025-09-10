# TARGET MISSIONS 
---

## SCANNING & SURVEILLANCE

**Mission 1: “Area Scan & Map (Multi-Altitude)”**
**Skills Used:** `arm, takeoff, up/down, orbit 360°, /take_photo, status, land`
**Operation:** `arm → takeoff <alt> → orbit 360° + /take_photo (every 2–3s) → up 4 → orbit 360° + /take_photo → down 8 → orbit 360° + /take_photo → land`

**Mission 2: “Perimeter Security Sweep → Intruder Verify”**
**Skills Used:** `goto <GPS>, forward/back/left/right, yaw_left/right, orbit, /take_photo`
**Operation:** `goto P1 → orbit 4 → /take_photo → goto P2 → orbit 4 → ... (all checkpoints) → on detection(person/vehicle): stop → goto <det.GPS> → orbit 3 → /take_photo → continue`

---

## INSPECTION

**Mission 3: “Structure Inspection (Oblique Rings)”**
**Skills Used:** `goto <GPS>, orbit, up/down, yaw, /take_photo`
**Operation:** `goto <structure> <alt> → orbit 10 cw + /take_photo → down 4 → orbit 12 ccw + /take_photo → close-in: forward 3 / yaw sweep + /take_photo → rtl`

---

## NAVIGATION & POSITIONING

**Mission 4: “GPS Waypoint Navigation + Photo Proof”**
**Skills Used:** `goto <GPS>, status, /take_photo, battery, rtl`
**Operation:** `takeoff <alt> → goto W1 → status + /take_photo → goto W2 → status + /take_photo → ... → battery check → rtl`

---

## SEARCH & TRACKING

**Mission 5: “Grid Search → Go-to Detection (SAR)”**
**Skills Used:** `forward/back/left/right (grid), yaw, /take_photo, goto <det.GPS>, orbit`
**Operation:** `takeoff <alt> → lawnmower grid (legs) + /take_photo → on detection(person): stop → goto <det.GPS> → orbit 5 → /take_photo → resume grid → rtl`

---

## AGRICULTURAL / ENVIRONMENTAL

**Mission 6: “Field Survey → Stress/Weed Tag”**
**Skills Used:** `goto field bounds, forward/back along rows, /take_photo, goto <det.GPS>, orbit`
**Operation:** `takeoff <alt> → row-aligned sweep + /take_photo → on detection(weed/stress): stop → goto <det.GPS> → orbit 3 → /take_photo (tag) → continue rows → rtl`

---
