Sampling hotel available rooms in a large area in a specific time window
---

Getting the number of available rooms is hard. Although we can exhausted search
all hotels in a large area, we still need to exhausted search the number of
available rooms of that hotel, which takes O(NK) time, N is the number of hotels,
K is the largest number of rooms in theses hotels. Therefore, in a limited time,
we need to adopt a sampling method to estimate the number of available rooms in hotels.

## Approaches

1. Random choose

2. RRZI with count(unbiased)

3. RRZI with hotel features.....(how to unbiased?)
