# NextDose: your child's road to health, booked.

![NextDose](logo.png?v=1b907797)

NextDose helps caregivers understand the next scheduled childhood immunisation visit and try a simulated clinic booking.

The interface uses Inter with a teal, mint and navy palette, a schedule progress track, a next-dose card and selectable day and time chips. See the [design mockup](design-mockup.html).

**Live prototype:** https://tibule12.github.io/NextDose/

**Prototype note:** All clinic appointments are simulated. No real health service booking is made, and the vaccination information requires clinical verification before real-world use.

## The African problem

Second measles dose coverage in South Africa was 76.2% in 2024/25 against a 95% target, down from 85.7% in 2016/17 (District Health Barometer, reported by Spotlight). Public clinic visits can take hours (about 3 hours measured at one Cape Town facility); some people pay up to R80 for someone to hold their place (GroundUp). For domestic workers, shift workers and spaza owners that is a day's income. The paper Road to Health booklet is easy to lose. Cape Town already has clinic booking; nothing starts from the child's due dose and books that visit.

## What NextDose does

1. Enter date of birth.
2. See the schedule with done / due / overdue / upcoming.
3. Tap Book on the next due dose and choose a clinic and time slot.
4. Get a confirmation with a reference number.

## Screenshots

.

## How to run

Clone the repo and open `index.html` in a browser. No install, no server, no sign-up.

## How we kept tokens low

We only built what was required for a functional delivery.

## Data and honesty notes

The schedule is copied from NDoH PHC Standard Treatment Guidelines, Chapter 13 Immunisation, section 13.2, p13.3 (Dec 2024), not generated; clinics and slots are demo data; data stays on the phone in browser storage.

## What's next

- WhatsApp/SMS reminders
- Booking into City of Cape Town and Western Cape Health systems
- MomConnect as a channel
- Nurse view of overdue children
- isiXhosa, isiZulu and Afrikaans

## Team

Prince Rammalo, Thulani Mtshwelo, Dangton Phiphira, Cliff Kibalama.
