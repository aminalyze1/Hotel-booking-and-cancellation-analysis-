# Hotel Booking & Cancellation Analysis

Why do hotel guests cancel their reservations, and what can a hotel do about it?

This project analyses **52,243 hotel bookings** to find the factors behind cancellations. The results are shown in an interactive Excel dashboard.


## Business Questions

1. Why do guests cancel their reservations?
2. What factors are in play?
3. Which guests are most likely to cancel?
4. What patterns do cancelled bookings follow?
5. What can be done about it?

## Key Findings

| Metric | Result |
|---|---|
| Total reservations | 52,243 |
| Total cancellations | 22,534 |
| Cancellation rate | 43% |
| Total repeat guests | 1,707 |

- **Market segment:** Online Travel Agencies (Online TA) had the most cancellations, with 17,435. That is about 77% of all cancellations. Offline TA/TO was next with 1,871, then Direct with 1,588.
- **Deposit type:** "No Deposit" bookings had 21,716 cancellations, about 96% of the total. Non Refund had 792 and Refundable had 26.
- **Room type:** Room type A had the most cancellations (13,608), followed by D (4,975) and E (1,612).
- **Lead time:** Bookings made far in advance had the highest cancellation rate. "Extremely high" (100+ days) was 41.76%, Medium (60 days) was 25.00%, High (100 days) was 17.14% and Short (20 days) was 16.10%.
- **Guest type:** First-time guests (people who booked but never stayed) made 22,462 of the 22,534 cancellations, about 99.7%. Only 72 cancellations came from repeat guests, which is about 4% of the 1,707 repeat guests.
- **Previous cancellations:** 747 guests had cancelled before. Of these, 553 (about 74%) had never stayed at the hotel, and 194 were repeat guests. A "first-time guest" here is someone who has made a reservation but never checked in.
- **Season:** Cancellations were highest in January to March and in July. June was the lowest month.

## Recommendations

1. **Promote direct bookings.** Offer exclusive perks, such as free breakfast, on the hotel's official website.
2. **Collect a deposit at booking.** Ask for a full or partial payment when the guest books.
3. **Watch long lead-time bookings.** These bookings are the most likely to be cancelled.
4. **Reward repeat guests.** They rarely cancel, so loyalty offers protect a reliable source of revenue.

## Tools Used

- Excel
- Power Query (data cleaning)
- Power Pivot
- Pivot tables and charts (interactive dashboard)

## Dataset

Public hotel booking dataset from Kaggle. It has more than 52,000 rows. The dashboard has a year filter for 2015, 2016 and 2017.

## Project Files

```
├── README.md
├── REPORT.md
├── images/
│   └── hotel-cancellation-dashboard.jpg
└── (add your Excel workbook here)
```

## Full Report

Read the full write-up in [REPORT.md](REPORT.md).

## Author

**Ariyibi Aminat**, Data & Business Analyst
GitHub: [aminalyze1](https://github.com/aminalyze1) | LinkedIn: aminat-ariyibi-2883b2262
